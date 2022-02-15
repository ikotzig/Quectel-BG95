# Quectel-BG95 driver

    AT

    OK
    ATI

    Quectel
    BG95-M3
    Revision: BG95M3LAR02A03

    OK
    ATV1

    OK
    ATE1

    OK
    AT+CMEE=2

    OK
    AT+CPIN=8417

    OK

    +CPIN: READY

    +QUSIM: 1
    AT+CREG?

    +CREG: 0,2

    OK

    +QIND: SMS DONE
    AT+COPS?

    +COPS: 0

    OK
    AT+CSQ

    +CSQ: 99,99

    OK
    AT+QICSGP=1,1,"Internet","","",0

    OK
    AT+QIACT=1

    ERROR
    AT+QIACT?

    OK
    AT+QIACT=1

    OK
    AT+QIACT?

    +QIACT: 1,1,1,"100.87.124.107"

    OK
    AT+COPS?

    +COPS: 0,0,"TELEKOM SK",0

    OK
    AT+QMTCFG="ssl",0,1,2

    OK
    AT+QSSLCFG="cacert",2,"cacert.pem"

    OK
    AT+QSSLCFG="clientcert",2,"client.pem"

    OK
    AT+QSSLCFG="clientkey",2,"user_key.pem"

    OK
    AT+QSSLCFG="seclevel",2,2

    OK
    AT+QSSLCFG="sslversion",2,4

    OK
    AT+QSSLCFG="ciphersuite",2,0XFFFF

    OK
    AT+QSSLCFG="ignorelocaltime",2,1

    OK
    AT+QMTOPEN=0,"a1je05qdpwq3dm-ats.iot.eu-west-2.amazonaws.com",8883

    OK

    +QMTOPEN: 0,0
    AT+QMTCONN=0,"quectel"

    OK

    +QMTCONN: 0,0,0
    AT+QMTSUB=0,1,"main_topic",1

    OK

    +QMTSUB: 0,1,0,1
    AT+QMTPUB=0,1,1,0,"main_topic"

    > AT+QMTPUBEX=0,1,1,0,"main_topic","Temperature: 22stC"

    OK

    +QMTPUB: 0,1,0

    +QMTRECV: 0,1,"main_topic","AT+QMTPUBEX=0,1,1,0,"main_topic","Temperature: 22stC"
    "
    AT+QMTPUBEX=0,1,1,0,"main_topic","Presure: 3.2Bar"

    OK

    +QMTPUB: 0,1,0

    +QMTRECV: 0,1,"main_topic","Presure: 3.2Bar"
    AT+QMTPUBEX=0,1,1,0,"main_topic","Temperature: 23stC"

    OK

    +QMTPUB: 0,1,0

    +QMTRECV: 0,1,"main_topic","Temperature: 23stC"
    AT+QMTPUBEX=0,1,1,0,"main_topic","Temperature: 23stC"

    OK

    +QMTPUB: 0,1,0

    +QMTRECV: 0,1,"main_topic","Temperature: 23stC"
    AT+QMTPUBEX=0,1,1,0,"main_topic","Presure: 3.2Bar"

    OK

    +QMTPUB: 0,1,0

    +QMTRECV: 0,1,"main_topic","Presure: 3.2Bar"
    AT+QMTPUBEX=0,1,1,0,"main_topic","Temperature: 24stC"

    OK

    +QMTPUB: 0,1,0

    +QMTRECV: 0,1,"main_topic","Temperature: 24stC"
    AT+QMTPUBEX=0,1,1,0,"main_topic","Presure: 3.3Bar"

    OK
