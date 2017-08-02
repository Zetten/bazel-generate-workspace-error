http_archive(
    name = "bazel_migration_tooling",
    sha256 = "ad0463105b00d003961916d9ad2a578c26deffb400d371f552d5118d5daf4277",
    strip_prefix = "migration-tooling-24f423d0fe9ca6589b87a12419d4657c61309e00",
    urls = ["https://github.com/bazelbuild/migration-tooling/archive/24f423d0fe9ca6589b87a12419d4657c61309e00.zip"],
)

load("@bazel_migration_tooling//:generate_workspace.bzl", "generated_maven_jars")

generated_maven_jars()
