# IETF_Hackathan_BGPCT_JUNOS_FreeRTR
Configuration files

IETF-115 Hackathon - BGP CT interop demo #1.

- Demonstrate BGP CT interop between JUNOS and RARE/FreeRTR
- Draft Link: https://datatracker.ietf.org/doc/draft-ietf-idr-bgp-ct/

#BGPCT #IETFHackathon #IETF115 #junipernetworks #RARE #FreeRTR

===========
 
Physical:

 
VMX1--------L1-------L2--------L3--------VMX2
 
Logical:
 
  [ce1]-----[pe1]---p1-----[asbr11]------[asbr21]---p2-----[asbr22]---[asbr31]----p3---[pe2]-----[ce2]

              (junos AS)                   (freeRtr AS)                  (junos AS)
 
