set(INC_ROOT ${PROJECT_SOURCE_DIR}/include)
set(SRC_ROOT ${PROJECT_SOURCE_DIR}/src)

set(SRC
    ${SRC_ROOT}/Main.cpp  

    ${INC_ROOT}/Core/Window/Window.hpp
    ${SRC_ROOT}/Core/Window/Window.cpp
)

add_executable(${PROJECT_NAME} ${SRC})
target_include_directories(${PROJECT_NAME} PRIVATE ${INC_ROOT})
