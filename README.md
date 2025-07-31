# helios-test-data

This project hosts test data for [HELIOS++](https://github.com/3dgeo-heidelberg/helios).

## Available datasets

* LAZ output for ALS multichannel and risley scanner demo: `data/surveys/demo/light_als_toyblocks_multiscanner.xml`
  * without splitting by channel:
    * `als_multichannel_leg000_points.laz`
    * `als_multichannel_leg002_points.laz`
  * split by channel (device):
    * `als_multichannel_split_leg000_points_dev0.laz`
    * `als_multichannel_split_leg000_points_dev1.laz`
    * `als_multichannel_split_leg000_points_dev2.laz`
    * `als_multichannel_split_leg002_points_dev0.laz`
    * `als_multichannel_split_leg002_points_dev1.laz`
    * `als_multichannel_split_leg002_points_dev2.laz`
* LAS output for TLS arbaro demo: `data/surveys/demo/tls_arbaro_demo.xml`
  * `arbaro_tls_leg000_points.las`
  * `arbaro_tls_leg001_points.las`
* LAS output for ULS detailedVoxels test: `test/uls_detailedVoxels_mode_comparison_min.xml`
  * `detailedVoxels_uls_leg000_points.las`
* LAZ output for dynamic scene demo: `data/surveys/dyn/tls_dyn_cube.xml`
  * `dyn_leg000_points.laz`
* LAZ output for interpolated trajectory demo: `data/surveys/demo/als_interpolated_trajectory.xml`
  * `interpolated_traj_leg000_points.laz`
  * `interpolated_traj_leg001_points.laz`
  * `interpolated_traj_leg002_points.laz`
  * `interpolated_traj_leg003_points.laz`
* LAZ output for quadcopter demo: `data/surveys/toyblocks/uls_toyblocks_survey_scene_combo.xml`
  * `quadcopter_leg000_points.laz`
  * `quadcopter_leg001_points.laz`
  * `quadcopter_leg002_points.laz`
  * `quadcopter_leg004_points.laz`
* LAS output for the geotiffloader test: `data/test/als_hd_demo_tiff_min.xml`
  * `tiffloader_als_leg000_points.las`
  * `tiffloader_als_leg001_points.las`
  * `tiffloader_als_leg002_points.las`
* LAS output for the xyzloader demo: `data/surveys/voxels/tls_sphere_xyzloader_normals.xml`
  * `xyzVoxels_tls_leg000_points.las`

## Download

Data can be downloaded as an archive from [the releases page](https://github.com/dokempf/helios-test-data/releases).
