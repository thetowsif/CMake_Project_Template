cmake_minimum_required(VERSION 3.28.3)
project(OSDetector)


file(GLOB SRC_FILES
	"src/*.cpp"
)

set(INC_FILES_DIR
	include/
)

include_directories(
	${INC_FILES_DIR}
)

add_executable(MyApp
	${SRC_FILES}
)
