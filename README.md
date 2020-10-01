# Arduino-Bluetooth-IR
This code is used to control electronic appliances using HC-05/HC-06 Bluetooth module    and TSOP38238 infrared receiver. This code runs on any Arduino board and controls a 4-channel relay to which the electronic devices are connected to the main board.

                   BLUTOOTH MODULE AND IR RECIEVER CONFIGURATION TO ARDUINO BOARD
                  ****************************************************************
  ARDUINO BOARD--------------HC05 MODULE--------------RELAY MODULE------------------IR RECIVER
  Vcc +5v                    Vcc +5v                  Vcc +5v                       Vcc +5v
  Gnd                        Gnd                      Gnd                           Gnd
  Txd                        RxD
  RxD                        TxD
  Pin 8                                               Channel 1
  Pin 9                                               Channel 2
  Pin 10                                              Channel 3
  Pin 11                                              Channel 4
  Pin 7                                                                             Pout


  On the app, you'll configure the following buttons with the corresponding values
  button channel one ------------ 1-off and 2-on
  button channel two ------------ 3-off and 4-on
  button channel three ---------- 5-off and 6-on
  button channel four ----------- 7-off and 8-on
