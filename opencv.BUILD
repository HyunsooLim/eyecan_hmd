cc_library(
    name = "opencv",
    #srcs = glob(["lib/*.dylib"]),# for mac
    srcs = glob(["lib/*.so*"]),
    hdrs = glob(["include/**/*.hpp"]),
    includes = ["include"],
    visibility = ["//visibility:public"], 
    linkstatic = 1,
)