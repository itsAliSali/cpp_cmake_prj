CMAKE_MINIMUM_REQUIRED(VERSION 3.1)

SET(EXECUTABLE_NAME prog1)

SET(SRC
	prog1.cpp
)

ADD_EXECUTABLE(${EXECUTABLE_NAME} ${SRC})

TARGET_LINK_LIBRARIES(${EXECUTABLE_NAME} ${LIBS})