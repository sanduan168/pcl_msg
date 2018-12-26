workspace(name = "pcl_msgs")

git_repository(
    name = "io_bazel_rules_ros",
    remote = "http://git.gs-robot.com/bazel-build/rules_ros.git",
    commit = "6f1e1e04a13717f229e1c2b76ec6dd5a34420f26",
)
load("@io_bazel_rules_ros//ros:ros.bzl", "ros_repositories")

ros_repositories()
