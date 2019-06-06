load("@build_bazel_rules_android//android:rules.bzl", "android_binary")

package(
    default_visibility = ["//visibility:public"],
    licenses = ["notice"],  # Apache 2.0
)

android_binary(
    name = "SmartReplyDemo",
    srcs = glob([
        "java/**/*.kt",
        "java/**/*.java",
    ]),
    aapt_version = "aapt",
    assets = [":assets"],
    assets_dir = "",
    custom_package = "lt.setkus.smartreply",
    manifest = "AndroidManifest.xml",
    resource_files = glob(["res/**"]),
    deps = [
        "@androidsdk//com.android.support:support-v13-25.2.0",
        "@androidsdk//com.android.support:support-v4-25.2.0",
    ],
)
