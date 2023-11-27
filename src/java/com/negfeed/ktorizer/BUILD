# Add a kotlin binary target for the Main.kt file.

load("@rules_kotlin//kotlin:jvm.bzl", "kt_jvm_binary")

kt_jvm_binary(
    name = "main",
    srcs = ["Main.kt"],
    main_class = "MainKt",
)

kt_jvm_binary(
    name = "main_ktor",
    srcs = ["MainKtor.kt"],
    main_class = "MainKtorKt",
    deps = ["@maven//:io_ktor_ktor_server_netty_jvm", "@maven//:io_ktor_ktor_server_core_jvm"],
)
