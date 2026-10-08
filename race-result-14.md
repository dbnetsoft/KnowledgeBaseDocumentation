# RACE RESULT 14

## Exporter for ALGE-Timing Emulation

Use the following exporter string to emulate an ALGE-Timing device to be received in software that dies not support RR14 natively.

{% code overflow="wrap" %}
```
"" & right("0000" & [Bib];4) & " " & switch([RD_TimingPoint]="START";"C0 ";[RD_TimingPoint]="FINISH";"C1 ";1;"C9 ") & " " & format([RD_Time]-86400int([RD_Time]/86400);"hhss.kkkk") & " "
```
{% endcode %}
