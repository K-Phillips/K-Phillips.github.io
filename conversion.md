---
title: Conversion to Xigt
---

# About FLex to Xigt

This is where we put some stuff about the conversion 

## Example Xigt

```xml
  <igt id="igt1">
    <tier id="p" type="phrases">
      <item id="p1">ihé pres əmə ləybədubu kədaywaydəno ?</item>
    </tier>
    <tier id="w" type="words" segmentation="p">
      <item id="w1" segmentation="p1[0:2]">ihé</item>
      <item id="w2" segmentation="p1[4:7]">pres</item>
      <item id="w3" segmentation="p1[9:11]">əmə</item>
      <item id="w4" segmentation="p1[13:21]">ləybədubu</item>
      <item id="w5" segmentation="p1[23:34]">kədaywaydəno</item>
      <item id="w6" segmentation="p1[36:36]">?</item>
    </tier>
    <tier id="m" type="morphemes" segmentation="w">
      <item id="m1.1" type="stem" segmentation="w1[0:2]">ihé</item>
      <item id="m2.1" type="stem" segmentation="w2[4:7]">pres</item>
      <item id="m3.1" type="prefix" segmentation="w3[9:9]">ə-</item>
      <item id="m3.2" type="stem" segmentation="w3[10:11]">mə</item>
      <item id="m4.1" type="stem" segmentation="w4[13:15]">ləy</item>
      <item id="m4.2" type="suffix" segmentation="w4[16:17]">-bə</item>
      <item id="m4.3" type="enclitic" segmentation="w4[18:19]">=du</item>
      <item id="m4.4" type="enclitic" segmentation="w4[20:21]">=bu</item>
      <item id="m5.1" type="stem" segmentation="w5[23:27]">kəday</item>
      <item id="m5.2" type="stem" segmentation="w5[28:30]">way</item>
      <item id="m5.3" type="enclitic" segmentation="w5[31:32]">=də</item>
      <item id="m5.4" type="enclitic" segmentation="w5[33:34]">=no</item>
    </tier>
    <tier id="g" type="glosses" alignment="m">
      <item id="g1.1">(intj)</item>
      <item id="g2.1">press</item>
      <item id="g3.1">ATT-</item>
      <item id="g3.2">one</item>
      <item id="g4.1">be</item>
      <item id="g4.2">-NOM</item>
      <item id="g4.3">==DDET</item>
      <item id="g4.4">==ADVR</item>
      <item id="g5.1">where</item>
      <item id="g5.2">thereabouts</item>
      <item id="g5.3">==LOC</item>
      <item id="g5.4">==INQ</item>
    </tier>
    <tier id="msa" type="msa" alignment="m">
      <item id="msa1.1">interj </item>
      <item id="msa2.1">n </item>
      <item id="msa3.1">Attaches to any category</item>
      <item id="msa3.2">Not Sure</item>
      <item id="msa4.1">v </item>
      <item id="msa4.2">v n</item>
      <item id="msa4.3">Not Sure</item>
      <item id="msa4.4">Not Sure</item>
      <item id="msa5.1">adv </item>
      <item id="msa5.2">Not Sure</item>
      <item id="msa5.3">Not Sure</item>
      <item id="msa5.4">Not Sure</item>
    </tier>
    <tier id="cf" type="cf" alignment="m">
      <item id="cf1.1">ihé</item>
      <item id="cf2.1">pres</item>
      <item id="cf3.1">ə́-</item>
      <item id="cf3.2">mə</item>
      <item id="cf4.1">ləy</item>
      <item id="cf4.2">-pə</item>
      <item id="cf4.3">tú</item>
      <item id="cf4.4">=pu</item>
      <item id="cf5.1">kəday</item>
      <item id="cf5.2">way</item>
      <item id="cf5.3">=tə</item>
      <item id="cf5.4">=no</item>
    </tier>
    <tier id="x" type="syntax" alignment="w">
      <item id="x1" alignment="w1">interj</item>
      <item id="x2" alignment="w2">n</item>
    </tier>
    <tier id="t" type="translations" alignment="p">
      <item id="t1">By the way, do you know the whereabouts of that printing press?</item>
    </tier>
  </igt>
```
