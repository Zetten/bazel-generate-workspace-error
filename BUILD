genrule(
    name = "test_generate_workspace",
    srcs = ["pom.xml"],
    outs = ["generate_workspace.bzl"],
    cmd = "$(location @bazel_migration_tooling//generate_workspace) --maven_project=$$(dirname $(location pom.xml)) --output_dir=$$(dirname $@)",
    tools = ["@bazel_migration_tooling//generate_workspace"],
)
