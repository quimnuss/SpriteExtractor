project(SpriteExtractor)

set(SOURCES main.c)
add_executable(sprite_extractor ${SOURCES})
target_link_libraries(sprite_extractor m)
