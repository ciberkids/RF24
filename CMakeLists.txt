


generate_arduino_library(RF24Lib
        BOARD ${BOARD}
        SRCS RF24.cpp
        HDRS RF24_config.h RF24.h
        LIBS SPILib
        )
