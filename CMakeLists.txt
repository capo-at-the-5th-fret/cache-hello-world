cmake_minimum_required(VERSION 3.13)
project(Foo LANGUAGES CXX)

### Build settings
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_INSTALL_RPATH_USE_LINK_PATH TRUE)

set(SOURCES
	main.cpp)

set(HEADERS
)

set(RESOURCES
)

set (FORMS
)

add_executable(foo
	${SOURCES} ${HEADERS} ${RESOURCES}
	${FORMS})
