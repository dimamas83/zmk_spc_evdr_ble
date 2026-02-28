# Добавляем путь к щитам в глобальный список Zephyr
list(APPEND SHIELD_PATH ${CMAKE_CURRENT_LIST_DIR}/boards/shields)

# Это поможет нам увидеть в логах, что файл прочитан
message(STATUS "ZMK Config Module: Registered shields from ${CMAKE_CURRENT_LIST_DIR}/boards/shields")
