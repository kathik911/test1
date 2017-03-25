[local]
;exten => _X.,1,Dial(SIP/${EXTEN}@9404)
;exten => _X.,n,Hangup()
;exten => 700,1,Answer
;exten => 700,1,MusicOnHold()
exten => 9404,1,Dial(SIP/@9404)
exten => 9404,n,Hangup()

exten => 9405,1,Dial(SIP/@9405)
exten => 9405,n,Hangup()
exten => _X.,1,Dial(SIP/${EXTEN}@sipp)
same =>Hangup
exten => _+X.,1,Dial(SIP/${EXTEN}@sipp)
same =>Hangup
exten => 30030,1,Dial(SIP/@30030)
exten => 30030,n,Hangup()
exten => 700,1,NoOP()
exten => 700,n,Dial(SIP/${ARG1}@9404,${RINGTIME},${CALLERID})
exten => 666,1,Dial(SIP/${EXTEN}@sipfra
exten => 777,1,Dial(SIP/${EXTEN}@sipfra)
[dinesh]

exten => 7984,1,Dial(SIP/@7984)
exten => 7984,n,Hangup()
exten => 9876,1,Dial(SIP/@9876)
exten => 9876,n,Hangup()
exten => 5788,1,Dial(SIP/@5788)
exten => 5788,n,Hangup()
exten => 53035,1,Dial(SIP/@53035)
exten => 53035,n,Hangup()
exten => 30030,1,Dial(SIP/@30030)
exten => 30030,n,Hangup()
exten => 0175,1,Dial(SIP/@0175)
exten =>  0175,n,Hangup()
exten => 11312,1,Dial(SIP/@11312)
exten => 11312,n,Hangup()
exten => 666,1,Dial(SIP/${EXTEN}@sipfra)
exten => 0077,1,Dial(SIP/${EXTEN}@0077)
exten => 0077,n,Hangup()
exten => 9404,1,Dial(SIP/${EXTEN}@9404)
