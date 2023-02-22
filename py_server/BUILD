package(default_visibility = ["//visibility:public"])

py_binary(
    name = "server",
    srcs = ["server.py"],
    data = [
        "//hello_lib:hello_lib_wasm",
        "//static:fe_static",
    ]
)