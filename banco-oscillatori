import("stdfaust.lib");
freq= vslider("[01] frequenza", 440,20,20000,1);
gain1= vslider("[02]amp1", 0. , 0. , 1. ,  0.01);
gain2= vslider("[03]amp2", 0. , 0. , 1. ,  0.01);
gain3= vslider("[04]amp3", 0. , 0. , 1. ,  0.01);
gain4= vslider("[05]amp4", 0. , 0. , 1. ,  0.01);
gain5= vslider("[06]amp5", 0. , 0. , 1. ,  0.01);
gain6= vslider("[07]amp6", 0. , 0. , 1. ,  0.01);
gain7= vslider("[08]amp7", 0. , 0. , 1. ,  0.01);
gain8= vslider("[09]amp8", 0. , 0. , 1. ,  0.01);
gain9= vslider("[10]amp9", 0. , 0. , 1. ,  0.01);
gain10= vslider("[11]amp10", 0. , 0. , 1. ,  0.01);
gain11= vslider("[12]amp11", 0. , 0. , 1. ,  0.01);
gain12= vslider("[13]amp12", 0. , 0. , 1. ,  0.01);
gain13= vslider("[14]amp13", 0. , 0. , 1. ,  0.01);
gain14= vslider("[15]amp14", 0. , 0. , 1. ,  0.01);
gain15= vslider("[16]amp15", 0. , 0. , 1. ,  0.01);
gain16= vslider("[17]amp16", 0. , 0. , 1. ,  0.01);
process = hgroup("banco di oscillatori armonici",
    os.osc(freq*1) *(gain1),
    os.osc(freq*2) *(gain2),
    os.osc(freq*3) *(gain3),
    os.osc(freq*4) *(gain4),
    os.osc(freq*5) *(gain5),
    os.osc(freq*6) *(gain6),
    os.osc(freq*7) *(gain7),
    os.osc(freq*8) *(gain8),
    os.osc(freq*9) *(gain9),
    os.osc(freq*10) *(gain10),
    os.osc(freq*11) *(gain11),
    os.osc(freq*12) *(gain12),
    os.osc(freq*13) *(gain13),
    os.osc(freq*14) *(gain14),
    os.osc(freq*15) *(gain15),
    os.osc(freq*16) *(gain16))
     :> _ <: _,_;

