package(default_visibility = ["//visibility:public"])

load("@rules_rust//rust:defs.bzl", "rust_shared_library")
load("@rules_rust//wasm_bindgen:wasm_bindgen.bzl", "rust_wasm_bindgen")

rust_shared_library(
    name = "hello_lib",
    srcs = ["src/lib.rs"],
    edition = "2018",
    deps = [
        "@rules_rust//wasm_bindgen/3rdparty:wasm_bindgen",
    ]
)

rust_wasm_bindgen(
    name = "hello_lib_wasm",
    target = "web",
    wasm_file = ":hello_lib",
)