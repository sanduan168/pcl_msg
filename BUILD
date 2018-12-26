# Bazel (http://bazel.io/) BUILD file for pcl_msgs

cc_library(
    name = "pcl_msgs",
    hdrs = glob([
        "ros_gen/pcl_msgs/*.h",
    ]),
    includes = [
        "ros_gen",
    ],
    copts = [],
    linkopts = [],
    deps = [
        "@io_bazel_rules_ros//ros:sensor_msgs",
        "@io_bazel_rules_ros//ros:std_msgs",
    ],
    visibility = ["//visibility:public"],
)
