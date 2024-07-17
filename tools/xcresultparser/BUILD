genrule(
    name = "xcresultparser",
    srcs = [
        "@xcresultparser",
    ],
    outs = ["xcresultparser_bin"],
    cmd = "cat $(locations @xcresultparser) > $@",
    executable = True,
    visibility = ["//:__subpackages__"],
)
