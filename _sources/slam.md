# SLAM

**Simultaneous Localization and Mapping** or **SLAM** is a method in robotics to *localize* a robot in a *map* that is being built on the fly. GTSAM supports SLAM as a nonlinear optimization problem, and provides many types of factors to help practitioners.

The following examples are provided

- Pose2SLAMExample: 2D pose-SLAM, where only poses are optimized for subject to pose-constraints, e.g., derived from successive LIDAR scans.
- Pose2ISAM2Example: an incremental pose-SLAM example, using the iSAM2 algorithm.
- Pose2SLAMExample_g2o: SLAM: a larger 2D SLAM example showing off how to read g2o files.
- PlanarSLAMExample: 2D SLAM with bearing-range measurements to 2D landmarks


