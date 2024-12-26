include_directories("../include/")

add_library(
  ${PROJECT_NAME}
  "*.cpp"
)

add_executable(
  ${PROJECT_NAME}
  "main.cpp"
)
target_include_directories(${PROJECT_NAME} PRIVATE ${HEADER_DIR})
