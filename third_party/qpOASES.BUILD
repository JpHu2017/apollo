licenses(["notice"])

package(default_visibility = ["//visibility:public"])

licenses(["notice"])
exports_files(["googletest/LICENSE"])

cc_library(
    name = "qpOASES",
    includes = [
        ".",
        "include",
        "src",
    ],
    srcs = [
        "src/BLASReplacement.cpp",
        "src/Bounds.cpp",
        "src/Constraints.cpp",
        "src/Flipper.cpp",
        "src/Indexlist.cpp",
        "src/LAPACKReplacement.cpp",
        "src/Matrices.cpp",
        "src/MessageHandling.cpp",
        "src/Options.cpp",
        "src/OQPinterface.cpp",
        "src/QProblemB.cpp",
        "src/QProblem.cpp",
        "src/SolutionAnalysis.cpp",
        "src/SparseSolver.cpp",
        "src/SQProblem.cpp",
        "src/SQProblemSchur.cpp",
        "src/SubjectTo.cpp",
        "src/Utils.cpp",
    ],
    hdrs = [
        "include/qpOASES/Types.hpp",
        "include/qpOASES/SQProblemSchur.ipp",
        "include/qpOASES/Matrices.hpp",
        "include/qpOASES/Constraints.ipp",
        "include/qpOASES/MessageHandling.ipp",
        "include/qpOASES/QProblem.ipp",
        "include/qpOASES/Utils.hpp",
        "include/qpOASES/Constraints.hpp",
        "include/qpOASES/Indexlist.hpp",
        "include/qpOASES/Options.hpp",
        "include/qpOASES/SparseSolver.hpp",
        "include/qpOASES/QProblemB.ipp",
        "include/qpOASES/UnitTesting.hpp",
        "include/qpOASES/ConstraintProduct.hpp",
        "include/qpOASES/Indexlist.ipp",
        "include/qpOASES/LapackBlasReplacement.hpp",
        "include/qpOASES/Flipper.hpp",
        "include/qpOASES/QProblem.hpp",
        "include/qpOASES/Constants.hpp",
        "include/qpOASES/SQProblem.ipp",
        "include/qpOASES/Utils.ipp",
        "include/qpOASES/Bounds.ipp",
        "include/qpOASES/Bounds.hpp",
        "include/qpOASES/SQProblem.hpp",
        "include/qpOASES/SQProblemSchur.hpp",
        "include/qpOASES/SubjectTo.ipp",
        "include/qpOASES/SubjectTo.hpp",
        "include/qpOASES/extras/OQPinterface.hpp",
        "include/qpOASES/extras/SolutionAnalysis.hpp",
        "include/qpOASES/extras/SolutionAnalysis.ipp",
        "include/qpOASES/MessageHandling.hpp",
        "include/qpOASES/QProblemB.hpp",
        "include/qpOASES.hpp",
    ],
    copts = [
        "-Wall",
        "-pedantic",
        "-Wshadow",
        "-Wfloat-equal",
        "-O3",
        "-Wconversion",
        "-Wsign-conversion",
        "-fPIC",
        "-DLINUX",
        "-DSOLVER_NONE",
        "-D__NO_COPYRIGHT__",
    ],
    include_prefix = "qpOASES",
    visibility = ["//visibility:public"],
)
