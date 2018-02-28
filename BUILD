COMPILER_OPTS = [
    "-DNDEBUG=1",
    "-DHAVE_FDATASYNC=1",
]

cc_library(
	name = "sqlite3",
	hdrs = [
		"sqlite3.h",
		"sqlite3ext.h"
	],
	srcs = [
		"sqlite3.c"
	],
	copts = ["-DSQLITE_CORE"] + COMPILER_OPTS,
)