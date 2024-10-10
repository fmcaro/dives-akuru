## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[19] NotoSerifDivesAkuru-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1861, but got 1069 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 764, but got 710 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Space and non-breaking space have differing width: The space glyph named space is 300 font units wide, non-breaking space named (uni00A0) is 260 font units wide, and both should be positive and the same. GlyphsApp has &quot;Sidebearing arithmetic&quot; (<a href="https://glyphsapp.com/tutorials/spacing">https://glyphsapp.com/tutorials/spacing</a>) which allows you to set the non-breaking space width to always equal the space width.</p>
 [code: different-widths]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check that texts shape as per expectation <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>qa/shaping_tests/issues.json: Expected and actual shaping not matching</p>
<ul>
<li>
<p>Shaping did not match: 𑤌𑤾𑤌𑤌𑤌 𑤛𑤾𑤠𑤛𑤠 (#9)</p>
<pre><code>Expected: None
Got     : u1190C=0+1322|u1193E=0+283|u1190C=2+1292|u1190C=3+1292|u1190C=4+1322|space=5+300|u1191B=6+1055|u1193E=6+283|u11920=8+1587|u1191B=9+1040|u11920=10+1667
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -710 11443 1779" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g28" d="M371.0,-159.0Q104.0,-159.0 104.0,-37.0Q104.0,7.0 153.5,50.0Q203.0,93.0 313.0,135.0Q310.0,149.0 310.0,164.0Q310.0,192.0 320.0,220.0Q217.0,223.0 166.0,259.0Q115.0,295.0 115.0,343.0Q115.0,393.0 171.5,433.0Q228.0,473.0 328.0,497.0Q428.0,521.0 558.0,521.0Q618.0,521.0 669.5,515.5Q721.0,510.0 763.0,500.0Q873.0,527.0 963.0,527.0Q1041.0,527.0 1105.5,504.0Q1170.0,481.0 1208.5,437.0Q1247.0,393.0 1247.0,330.0Q1247.0,272.0 1209.5,213.5Q1172.0,155.0 1106.5,100.5Q1041.0,46.0 955.0,-1.5Q869.0,-49.0 771.0,-84.0Q673.0,-119.0 571.0,-139.0Q469.0,-159.0 371.0,-159.0ZM222.0,-7.0Q222.0,-41.0 246.0,-60.5Q270.0,-80.0 312.0,-88.5Q354.0,-97.0 407.0,-97.0Q483.0,-97.0 565.0,-81.5Q647.0,-66.0 728.0,-37.5Q809.0,-9.0 881.0,29.5Q953.0,68.0 1008.5,113.5Q1064.0,159.0 1096.0,209.0Q1128.0,259.0 1128.0,310.0Q1128.0,351.0 1108.5,387.5Q1089.0,424.0 1045.0,447.0Q1001.0,470.0 929.0,470.0Q898.0,470.0 862.0,466.0Q912.0,441.0 936.5,408.0Q961.0,375.0 961.0,338.0Q961.0,295.0 934.0,257.0Q907.0,219.0 861.0,192.5Q815.0,166.0 758.0,156.0Q743.0,115.0 703.0,81.0Q663.0,47.0 610.0,27.0Q557.0,7.0 502.0,7.0Q442.0,7.0 395.0,32.0Q348.0,57.0 326.0,99.0Q269.0,71.0 245.5,44.5Q222.0,18.0 222.0,-7.0ZM233.0,347.0Q233.0,333.0 241.5,316.0Q250.0,299.0 273.5,284.5Q297.0,270.0 342.0,262.0Q381.0,322.0 457.5,372.0Q534.0,422.0 625.0,457.0Q581.0,461.0 533.0,461.0Q441.0,461.0 373.5,445.5Q306.0,430.0 269.5,404.0Q233.0,378.0 233.0,347.0ZM421.0,186.0Q421.0,156.0 435.5,129.0Q450.0,102.0 476.5,85.5Q503.0,69.0 538.0,69.0Q571.0,69.0 598.0,83.0Q625.0,97.0 641.0,119.0Q657.0,141.0 657.0,166.0Q657.0,201.0 629.5,231.5Q602.0,262.0 567.0,272.0L567.0,280.0L663.0,317.0Q702.0,307.0 730.0,278.0Q758.0,249.0 764.0,211.0Q798.0,216.0 819.0,233.5Q840.0,251.0 849.5,274.0Q859.0,297.0 859.0,318.0Q859.0,362.0 824.0,391.5Q789.0,421.0 730.0,438.0Q672.0,421.0 616.5,395.5Q561.0,370.0 517.0,337.5Q473.0,305.0 447.0,267.0Q421.0,229.0 421.0,186.0Z"/> <path id="g797" d="M100.0,-214.0L100.0,-160.0L253.0,-160.0L253.0,0.0L313.0,0.0L313.0,-160.0L466.0,-160.0L466.0,-214.0L313.0,-214.0L313.0,-376.0L253.0,-376.0L253.0,-214.0L100.0,-214.0Z"/> <path id="g450" d=""/> <path id="g36" d="M306.0,-196.0Q218.0,-196.0 163.5,-179.5Q109.0,-163.0 84.5,-134.5Q60.0,-106.0 60.0,-71.0Q60.0,-31.0 89.5,5.0Q119.0,41.0 167.0,69.5Q215.0,98.0 269.0,117.0Q275.0,148.0 297.5,177.5Q320.0,207.0 353.0,232.0Q284.0,237.0 241.0,274.0Q198.0,311.0 198.0,361.0Q198.0,400.0 224.5,434.0Q251.0,468.0 299.5,488.5Q348.0,509.0 412.0,509.0Q505.0,509.0 574.0,464.5Q643.0,420.0 674.0,351.0Q704.0,354.0 731.0,354.0Q805.0,354.0 861.0,332.0Q917.0,310.0 948.5,270.0Q980.0,230.0 980.0,176.0Q980.0,118.0 941.0,63.0Q902.0,8.0 834.5,-39.0Q767.0,-86.0 680.5,-121.0Q594.0,-156.0 498.0,-176.0Q402.0,-196.0 306.0,-196.0ZM310.0,374.0Q310.0,338.0 338.0,309.0Q366.0,280.0 407.0,268.0Q479.0,308.0 563.0,329.0Q539.0,379.0 496.5,415.5Q454.0,452.0 403.0,452.0Q366.0,452.0 338.0,431.5Q310.0,411.0 310.0,374.0ZM413.0,-15.0Q352.0,-15.0 315.5,10.5Q279.0,36.0 270.0,73.0Q232.0,51.0 203.5,20.5Q175.0,-10.0 175.0,-45.0Q175.0,-83.0 214.5,-108.5Q254.0,-134.0 345.0,-134.0Q412.0,-134.0 484.0,-120.0Q556.0,-106.0 623.0,-79.5Q690.0,-53.0 744.0,-17.0Q798.0,19.0 830.0,63.0Q862.0,107.0 862.0,156.0Q862.0,194.0 840.0,227.0Q818.0,260.0 780.5,280.5Q743.0,301.0 696.0,301.0Q693.0,301.0 689.0,301.0Q694.0,277.0 694.0,253.0Q694.0,196.0 670.5,147.0Q647.0,98.0 607.0,62.0Q567.0,26.0 517.0,5.5Q467.0,-15.0 413.0,-15.0ZM378.0,120.0Q378.0,88.0 396.5,67.5Q415.0,47.0 446.0,47.0Q482.0,47.0 514.5,72.5Q547.0,98.0 567.5,139.5Q588.0,181.0 588.0,227.0Q588.0,253.0 581.0,282.0Q485.0,259.0 431.5,216.5Q378.0,174.0 378.0,120.0Z"/> <path id="g41" d="M599.0,-9.0Q512.0,-9.0 475.0,14.5Q438.0,38.0 438.0,73.0Q438.0,96.0 452.5,114.0Q467.0,132.0 486.0,148.0Q509.0,168.0 531.5,189.0Q554.0,210.0 569.0,236.5Q584.0,263.0 584.0,298.0Q584.0,342.0 561.0,375.5Q538.0,409.0 500.5,427.5Q463.0,446.0 419.0,446.0Q367.0,446.0 311.5,423.0Q256.0,400.0 223.0,356.0Q229.0,357.0 235.0,357.0Q282.0,357.0 307.5,329.0Q333.0,301.0 333.0,267.0Q333.0,237.0 313.5,210.0Q294.0,183.0 262.0,166.5Q230.0,150.0 191.0,150.0Q141.0,150.0 108.0,179.0Q75.0,208.0 75.0,254.0Q75.0,299.0 107.0,344.5Q139.0,390.0 193.5,427.0Q248.0,464.0 315.5,486.5Q383.0,509.0 454.0,509.0Q528.0,509.0 583.5,484.0Q639.0,459.0 670.5,416.0Q702.0,373.0 702.0,319.0Q702.0,278.0 685.5,247.5Q669.0,217.0 646.5,195.5Q624.0,174.0 605.0,157.0Q586.0,140.0 573.5,126.0Q561.0,112.0 561.0,97.0Q561.0,77.0 583.5,65.0Q606.0,53.0 661.0,53.0Q790.0,53.0 910.5,68.5Q1031.0,84.0 1134.0,110.0Q1237.0,136.0 1314.0,169.5Q1391.0,203.0 1434.0,239.5Q1477.0,276.0 1477.0,311.0Q1477.0,340.0 1458.0,353.0Q1439.0,366.0 1404.0,366.0Q1376.0,366.0 1330.5,358.5Q1285.0,351.0 1235.0,335.0L1223.0,378.0Q1301.0,406.0 1364.0,418.5Q1427.0,431.0 1468.0,431.0Q1533.0,431.0 1562.5,407.0Q1592.0,383.0 1592.0,344.0Q1592.0,290.0 1542.5,238.0Q1493.0,186.0 1402.0,141.5Q1311.0,97.0 1187.0,63.0Q1063.0,29.0 914.0,10.0Q765.0,-9.0 599.0,-9.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g28"/> </g> <g transform="translate(1322,0)"> <use href="#g797"/> </g> <g transform="translate(1605,0)"> <use href="#g28"/> </g> <g transform="translate(2897,0)"> <use href="#g28"/> </g> <g transform="translate(4189,0)"> <use href="#g28"/> </g> <g transform="translate(5511,0)"> <use href="#g450"/> </g> <g transform="translate(5811,0)"> <use href="#g36"/> </g> <g transform="translate(6866,0)"> <use href="#g797"/> </g> <g transform="translate(7149,0)"> <use href="#g41"/> </g> <g transform="translate(8736,0)"> <use href="#g36"/> </g> <g transform="translate(9776,0)"> <use href="#g41"/> </g> </svg></p>
</li>
<li>
<p>Shaping did not match: 𑤿𑤧𑤵𑤿𑤤𑤱𑤿𑤢 (#10)</p>
<pre><code>Expected: u11935=0+405|u11927=0+455|u1193F=0@-66,-207+0|u11924=3+692|u1193F=3@-223,-137+0|u11931=3+347|u11922=6+745|u1193F=6@-296,-138+0
Got     : u11927_u11935=0+1413|u1193F=0@-923,-300+0|u11924_u11931=3+1390|u1193F=3@-1463,-391+0|u11922=6+1415|u1193F=6@-1370,-363+0
</code></pre>
<p>Got: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -710 4218 1781" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g269" d="M290.0,-15.0Q219.0,-15.0 181.5,18.5Q144.0,52.0 144.0,97.0Q144.0,134.0 167.5,168.5Q191.0,203.0 230.0,232.0Q161.0,237.0 118.0,274.0Q75.0,311.0 75.0,361.0Q75.0,400.0 101.5,434.0Q128.0,468.0 176.5,488.5Q225.0,509.0 289.0,509.0Q372.0,509.0 435.5,474.0Q499.0,439.0 535.0,381.0Q571.0,323.0 571.0,253.0Q571.0,196.0 547.5,147.0Q524.0,98.0 484.0,62.0Q444.0,26.0 394.0,5.5Q344.0,-15.0 290.0,-15.0ZM187.0,374.0Q187.0,338.0 215.0,309.0Q243.0,280.0 284.0,268.0Q356.0,308.0 440.0,329.0Q416.0,379.0 373.5,415.5Q331.0,452.0 280.0,452.0Q243.0,452.0 215.0,431.5Q187.0,411.0 187.0,374.0ZM255.0,120.0Q255.0,88.0 273.5,67.5Q292.0,47.0 323.0,47.0Q359.0,47.0 391.5,72.5Q424.0,98.0 444.5,139.5Q465.0,181.0 465.0,227.0Q465.0,253.0 458.0,282.0Q362.0,259.0 308.5,216.5Q255.0,174.0 255.0,120.0ZM993.0,-16.0Q917.0,-16.0 858.5,11.5Q800.0,39.0 766.5,85.5Q733.0,132.0 733.0,191.0Q733.0,266.0 792.0,342.0Q851.0,418.0 967.0,480.0Q911.0,494.0 844.0,501.5Q777.0,509.0 697.0,510.0L701.0,562.0Q721.0,563.0 741.5,563.5Q762.0,564.0 781.0,564.0Q965.0,564.0 1088.5,524.0Q1212.0,484.0 1275.0,415.5Q1338.0,347.0 1338.0,259.0Q1338.0,203.0 1309.5,153.0Q1281.0,103.0 1232.0,65.0Q1183.0,27.0 1121.5,5.5Q1060.0,-16.0 993.0,-16.0ZM849.0,208.0Q849.0,160.0 872.0,123.5Q895.0,87.0 934.5,67.0Q974.0,47.0 1023.0,47.0Q1079.0,47.0 1126.5,72.0Q1174.0,97.0 1203.0,141.0Q1232.0,185.0 1232.0,242.0Q1232.0,310.0 1184.0,366.5Q1136.0,423.0 1037.0,459.0Q949.0,415.0 899.0,346.5Q849.0,278.0 849.0,208.0Z"/> <path id="g781" d="M359.0,824.0L342.0,859.0Q395.0,891.0 426.0,922.5Q457.0,954.0 457.0,997.0Q457.0,1035.0 425.0,1059.0Q393.0,1083.0 339.0,1083.0Q309.0,1083.0 276.0,1074.5Q243.0,1066.0 222.0,1059.0L211.0,1098.0Q287.0,1118.0 331.0,1141.0Q375.0,1164.0 393.5,1188.0Q412.0,1212.0 412.0,1236.0Q412.0,1266.0 390.0,1285.5Q368.0,1305.0 336.0,1305.0Q284.0,1305.0 235.0,1262.0L207.0,1296.0Q242.0,1328.0 290.0,1349.5Q338.0,1371.0 390.0,1371.0Q453.0,1371.0 488.5,1340.5Q524.0,1310.0 524.0,1266.0Q524.0,1231.0 496.5,1195.5Q469.0,1160.0 415.0,1136.0Q421.0,1136.0 426.0,1136.0Q488.0,1136.0 527.5,1105.5Q567.0,1075.0 567.0,1030.0Q567.0,978.0 517.5,926.0Q468.0,874.0 359.0,824.0Z"/> <path id="g235" d="M270.0,-89.0Q270.0,-25.0 429.0,32.0Q611.0,131.0 611.0,264.0Q611.0,315.0 585.5,356.5Q560.0,398.0 515.5,423.0Q471.0,448.0 413.0,448.0Q352.0,448.0 298.5,420.5Q245.0,393.0 215.0,349.0Q225.0,350.0 235.0,350.0Q283.0,350.0 308.0,322.0Q333.0,294.0 333.0,262.0Q333.0,231.0 313.5,203.5Q294.0,176.0 262.5,159.5Q231.0,143.0 193.0,143.0Q141.0,143.0 108.0,172.0Q75.0,201.0 75.0,247.0Q75.0,299.0 106.0,346.0Q137.0,393.0 190.0,430.0Q243.0,467.0 309.5,488.0Q376.0,509.0 448.0,509.0Q538.0,509.0 601.0,477.0Q664.0,445.0 696.5,395.0Q729.0,345.0 729.0,290.0Q729.0,227.0 689.0,170.0Q649.0,113.0 586.0,76.0Q713.0,99.0 786.5,135.5Q860.0,172.0 891.5,213.0Q923.0,254.0 923.0,291.0Q923.0,321.0 911.0,351.0Q899.0,381.0 879.0,404.0L882.0,416.0Q909.0,430.0 947.0,442.5Q985.0,455.0 1028.5,463.0Q1072.0,471.0 1112.0,471.0Q1186.0,471.0 1235.5,447.5Q1285.0,424.0 1310.0,386.5Q1335.0,349.0 1335.0,307.0Q1335.0,260.0 1305.0,211.0Q1275.0,162.0 1223.5,115.5Q1172.0,69.0 1104.5,28.5Q1037.0,-12.0 962.0,-44.0Q867.0,-84.0 774.0,-111.0Q681.0,-138.0 597.0,-152.0Q513.0,-166.0 446.0,-166.0Q366.0,-166.0 318.0,-146.5Q270.0,-127.0 270.0,-89.0ZM385.0,-62.0Q385.0,-84.0 412.5,-95.0Q440.0,-106.0 488.0,-106.0Q541.0,-106.0 613.5,-93.0Q686.0,-80.0 770.0,-54.0Q854.0,-28.0 941.0,10.0Q1025.0,47.0 1087.0,92.5Q1149.0,138.0 1183.5,188.0Q1218.0,238.0 1218.0,286.0Q1218.0,322.0 1199.0,351.5Q1180.0,381.0 1147.5,398.5Q1115.0,416.0 1073.0,416.0Q1038.0,416.0 1002.0,406.0Q1017.0,388.0 1026.0,362.0Q1035.0,336.0 1035.0,309.0Q1035.0,250.0 974.5,189.0Q914.0,128.0 784.0,76.5Q654.0,25.0 445.0,-6.0Q385.0,-30.0 385.0,-62.0Z"/> <path id="g43" d="M845.0,-12.0Q747.0,-12.0 692.5,17.5Q638.0,47.0 638.0,94.0Q638.0,126.0 665.0,146.5Q692.0,167.0 727.0,186.0Q757.0,203.0 786.5,223.0Q816.0,243.0 835.0,270.5Q854.0,298.0 854.0,337.0Q854.0,380.0 827.0,416.0Q800.0,452.0 749.0,474.0Q698.0,496.0 626.0,496.0Q562.0,496.0 499.0,478.5Q436.0,461.0 380.5,429.5Q325.0,398.0 282.0,354.5Q239.0,311.0 215.0,258.0Q223.0,259.0 232.0,259.0Q280.0,259.0 306.5,230.5Q333.0,202.0 333.0,168.0Q333.0,138.0 313.5,111.5Q294.0,85.0 262.0,68.0Q230.0,51.0 192.0,51.0Q140.0,51.0 107.5,84.5Q75.0,118.0 75.0,164.0Q75.0,216.0 106.0,271.5Q137.0,327.0 192.0,378.0Q247.0,429.0 320.0,469.5Q393.0,510.0 477.5,534.0Q562.0,558.0 652.0,558.0Q717.0,558.0 775.0,545.0Q833.0,532.0 878.0,506.5Q923.0,481.0 949.0,444.0Q975.0,407.0 975.0,359.0Q975.0,316.0 953.5,284.5Q932.0,253.0 900.5,229.0Q869.0,205.0 838.0,186.0Q808.0,168.0 786.5,150.5Q765.0,133.0 765.0,112.0Q765.0,87.0 791.5,67.5Q818.0,48.0 876.0,48.0Q920.0,48.0 967.5,59.5Q1015.0,71.0 1060.5,91.0Q1106.0,111.0 1142.5,137.0Q1179.0,163.0 1201.0,191.5Q1223.0,220.0 1223.0,249.0Q1223.0,295.0 1169.0,295.0Q1152.0,295.0 1124.0,291.5Q1096.0,288.0 1063.0,280.0L1055.0,318.0Q1097.0,331.0 1149.0,342.5Q1201.0,354.0 1245.0,354.0Q1295.0,354.0 1317.5,335.5Q1340.0,317.0 1340.0,288.0Q1340.0,249.0 1313.5,207.5Q1287.0,166.0 1240.0,127.0Q1193.0,88.0 1130.5,56.5Q1068.0,25.0 995.0,6.5Q922.0,-12.0 845.0,-12.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g269"/> </g> <g transform="translate(490,-300)"> <use href="#g781"/> </g> <g transform="translate(1413,0)"> <use href="#g235"/> </g> <g transform="translate(1340,-391)"> <use href="#g781"/> </g> <g transform="translate(2803,0)"> <use href="#g43"/> </g> <g transform="translate(2848,-363)"> <use href="#g781"/> </g> </svg>  Expected: <svg style="height:100px;margin:10px;" xmlns="http://www.w3.org/2000/svg" viewBox="0 -710 3239 1944" transform="matrix(1 0 0 -1 0 0)"> <defs> <path id="g786" d="M290.0,-15.0Q219.0,-15.0 181.5,18.5Q144.0,52.0 144.0,97.0Q144.0,134.0 167.5,168.5Q191.0,203.0 230.0,232.0Q161.0,237.0 118.0,274.0Q75.0,311.0 75.0,361.0Q75.0,400.0 101.5,434.0Q128.0,468.0 176.5,488.5Q225.0,509.0 289.0,509.0Q372.0,509.0 435.5,474.0Q499.0,439.0 535.0,381.0Q571.0,323.0 571.0,253.0Q571.0,196.0 547.5,147.0Q524.0,98.0 484.0,62.0Q444.0,26.0 394.0,5.5Q344.0,-15.0 290.0,-15.0ZM187.0,374.0Q187.0,338.0 215.0,309.0Q243.0,280.0 284.0,268.0Q356.0,308.0 440.0,329.0Q416.0,379.0 373.5,415.5Q331.0,452.0 280.0,452.0Q243.0,452.0 215.0,431.5Q187.0,411.0 187.0,374.0ZM255.0,120.0Q255.0,88.0 273.5,67.5Q292.0,47.0 323.0,47.0Q359.0,47.0 391.5,72.5Q424.0,98.0 444.5,139.5Q465.0,181.0 465.0,227.0Q465.0,253.0 458.0,282.0Q362.0,259.0 308.5,216.5Q255.0,174.0 255.0,120.0Z"/> <path id="g50" d="M347.0,-16.0Q271.0,-16.0 212.5,11.5Q154.0,39.0 120.5,85.5Q87.0,132.0 87.0,191.0Q87.0,266.0 146.0,342.0Q205.0,418.0 321.0,480.0Q265.0,494.0 198.0,501.5Q131.0,509.0 51.0,510.0L55.0,562.0Q75.0,563.0 95.5,563.5Q116.0,564.0 135.0,564.0Q319.0,564.0 442.5,524.0Q566.0,484.0 629.0,415.5Q692.0,347.0 692.0,259.0Q692.0,203.0 663.5,153.0Q635.0,103.0 586.0,65.0Q537.0,27.0 475.5,5.5Q414.0,-16.0 347.0,-16.0ZM203.0,208.0Q203.0,160.0 226.0,123.5Q249.0,87.0 288.5,67.0Q328.0,47.0 377.0,47.0Q433.0,47.0 480.5,72.0Q528.0,97.0 557.0,141.0Q586.0,185.0 586.0,242.0Q586.0,310.0 538.0,366.5Q490.0,423.0 391.0,459.0Q303.0,415.0 253.0,346.5Q203.0,278.0 203.0,208.0Z"/> <path id="g781" d="M359.0,824.0L342.0,859.0Q395.0,891.0 426.0,922.5Q457.0,954.0 457.0,997.0Q457.0,1035.0 425.0,1059.0Q393.0,1083.0 339.0,1083.0Q309.0,1083.0 276.0,1074.5Q243.0,1066.0 222.0,1059.0L211.0,1098.0Q287.0,1118.0 331.0,1141.0Q375.0,1164.0 393.5,1188.0Q412.0,1212.0 412.0,1236.0Q412.0,1266.0 390.0,1285.5Q368.0,1305.0 336.0,1305.0Q284.0,1305.0 235.0,1262.0L207.0,1296.0Q242.0,1328.0 290.0,1349.5Q338.0,1371.0 390.0,1371.0Q453.0,1371.0 488.5,1340.5Q524.0,1310.0 524.0,1266.0Q524.0,1231.0 496.5,1195.5Q469.0,1160.0 415.0,1136.0Q421.0,1136.0 426.0,1136.0Q488.0,1136.0 527.5,1105.5Q567.0,1075.0 567.0,1030.0Q567.0,978.0 517.5,926.0Q468.0,874.0 359.0,824.0Z"/> <path id="g45" d="M465.0,-351.0Q343.0,-351.0 255.5,-328.5Q168.0,-306.0 121.5,-265.0Q75.0,-224.0 75.0,-169.0Q75.0,-126.0 104.5,-96.5Q134.0,-67.0 183.5,-45.0Q233.0,-23.0 291.0,-5.0Q348.0,13.0 404.5,37.5Q461.0,62.0 508.0,95.5Q555.0,129.0 583.0,173.0Q611.0,217.0 611.0,273.0Q611.0,353.0 559.5,400.5Q508.0,448.0 426.0,448.0Q376.0,448.0 321.5,425.5Q267.0,403.0 229.0,349.0Q240.0,350.0 250.0,350.0Q298.0,350.0 323.0,322.0Q348.0,294.0 348.0,262.0Q348.0,231.0 328.5,203.5Q309.0,176.0 277.5,159.5Q246.0,143.0 208.0,143.0Q156.0,143.0 123.0,172.0Q90.0,201.0 90.0,247.0Q90.0,298.0 120.5,345.0Q151.0,392.0 203.0,429.0Q255.0,466.0 319.5,487.5Q384.0,509.0 453.0,509.0Q534.0,509.0 596.5,479.5Q659.0,450.0 694.0,399.5Q729.0,349.0 729.0,286.0Q729.0,222.0 693.5,170.0Q658.0,118.0 600.0,77.0Q542.0,36.0 475.0,5.0Q408.0,-26.0 345.0,-48.0Q278.0,-71.0 235.5,-95.0Q193.0,-119.0 193.0,-163.0Q193.0,-218.0 264.5,-255.5Q336.0,-293.0 478.0,-293.0Q570.0,-293.0 647.5,-277.5Q725.0,-262.0 782.5,-237.5Q840.0,-213.0 872.0,-183.5Q904.0,-154.0 904.0,-127.0Q904.0,-107.0 884.5,-95.5Q865.0,-84.0 826.0,-84.0Q786.0,-84.0 715.5,-96.5Q645.0,-109.0 567.0,-132.0L555.0,-89.0Q665.0,-54.0 751.0,-38.5Q837.0,-23.0 886.0,-23.0Q960.0,-23.0 991.0,-47.5Q1022.0,-72.0 1022.0,-108.0Q1022.0,-150.0 981.5,-193.0Q941.0,-236.0 866.5,-272.0Q792.0,-308.0 690.0,-329.5Q588.0,-351.0 465.0,-351.0Z"/> <path id="g789" d="M381.0,-190.0Q221.0,-190.0 148.0,-161.0Q75.0,-132.0 75.0,-81.0Q75.0,-32.0 144.0,9.0Q213.0,50.0 346.0,69.0L353.0,32.0Q311.0,24.0 275.5,11.5Q240.0,-1.0 218.5,-17.5Q197.0,-34.0 197.0,-56.0Q197.0,-93.0 252.0,-112.0Q307.0,-131.0 425.0,-131.0Q525.0,-131.0 632.5,-118.0Q740.0,-105.0 846.5,-82.0Q953.0,-59.0 1048.0,-30.0Q1248.0,32.0 1358.0,115.5Q1468.0,199.0 1468.0,296.0Q1468.0,341.0 1445.5,376.0Q1423.0,411.0 1383.0,431.0Q1343.0,451.0 1291.0,451.0Q1257.0,451.0 1215.5,443.0Q1174.0,435.0 1135.0,424.0L1119.0,468.0Q1148.0,479.0 1186.0,488.0Q1224.0,497.0 1265.0,503.0Q1306.0,509.0 1342.0,509.0Q1424.0,509.0 1478.0,480.0Q1532.0,451.0 1558.5,407.0Q1585.0,363.0 1585.0,317.0Q1585.0,243.0 1524.5,168.0Q1464.0,93.0 1344.5,26.5Q1225.0,-40.0 1047.0,-91.0Q971.0,-112.0 865.0,-135.0Q759.0,-158.0 635.0,-174.0Q511.0,-190.0 381.0,-190.0Z"/> <path id="g43" d="M845.0,-12.0Q747.0,-12.0 692.5,17.5Q638.0,47.0 638.0,94.0Q638.0,126.0 665.0,146.5Q692.0,167.0 727.0,186.0Q757.0,203.0 786.5,223.0Q816.0,243.0 835.0,270.5Q854.0,298.0 854.0,337.0Q854.0,380.0 827.0,416.0Q800.0,452.0 749.0,474.0Q698.0,496.0 626.0,496.0Q562.0,496.0 499.0,478.5Q436.0,461.0 380.5,429.5Q325.0,398.0 282.0,354.5Q239.0,311.0 215.0,258.0Q223.0,259.0 232.0,259.0Q280.0,259.0 306.5,230.5Q333.0,202.0 333.0,168.0Q333.0,138.0 313.5,111.5Q294.0,85.0 262.0,68.0Q230.0,51.0 192.0,51.0Q140.0,51.0 107.5,84.5Q75.0,118.0 75.0,164.0Q75.0,216.0 106.0,271.5Q137.0,327.0 192.0,378.0Q247.0,429.0 320.0,469.5Q393.0,510.0 477.5,534.0Q562.0,558.0 652.0,558.0Q717.0,558.0 775.0,545.0Q833.0,532.0 878.0,506.5Q923.0,481.0 949.0,444.0Q975.0,407.0 975.0,359.0Q975.0,316.0 953.5,284.5Q932.0,253.0 900.5,229.0Q869.0,205.0 838.0,186.0Q808.0,168.0 786.5,150.5Q765.0,133.0 765.0,112.0Q765.0,87.0 791.5,67.5Q818.0,48.0 876.0,48.0Q920.0,48.0 967.5,59.5Q1015.0,71.0 1060.5,91.0Q1106.0,111.0 1142.5,137.0Q1179.0,163.0 1201.0,191.5Q1223.0,220.0 1223.0,249.0Q1223.0,295.0 1169.0,295.0Q1152.0,295.0 1124.0,291.5Q1096.0,288.0 1063.0,280.0L1055.0,318.0Q1097.0,331.0 1149.0,342.5Q1201.0,354.0 1245.0,354.0Q1295.0,354.0 1317.5,335.5Q1340.0,317.0 1340.0,288.0Q1340.0,249.0 1313.5,207.5Q1287.0,166.0 1240.0,127.0Q1193.0,88.0 1130.5,56.5Q1068.0,25.0 995.0,6.5Q922.0,-12.0 845.0,-12.0Z"/> </defs> <g transform="translate(0,0)"> <use href="#g786"/> </g> <g transform="translate(405,0)"> <use href="#g50"/> </g> <g transform="translate(794,-207)"> <use href="#g781"/> </g> <g transform="translate(860,0)"> <use href="#g45"/> </g> <g transform="translate(1329,-137)"> <use href="#g781"/> </g> <g transform="translate(1552,0)"> <use href="#g789"/> </g> <g transform="translate(1899,0)"> <use href="#g43"/> </g> <g transform="translate(2348,-138)"> <use href="#g781"/> </g> </svg></p>
</li>
</ul>
 [code: shaping-regression]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>No dotted circle glyph present and font uses a complex shaper</p>
 [code: missing-dotted-circle-complex]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
u1193E (U+1193E)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+1193F</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- u11929.alt2.undera

- u11935.undera

- u11937.undera
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphnames.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
dda_medya_iVoweldivesakuru.undera, ha_medra_aaVoweldivesakuru.undera, ha_medya_iVoweldivesakuru.undera, ka_medra_uVoweldivesakuru.undera, ka_medya_iVoweldivesakuru.undera, lla_medya_iVoweldivesakuru.undera, ma_medya_eVoweldivesakuru.undera, ma_medya_iVoweldivesakuru.undera, ma_medya_iiVoweldivesakuru.undera, na_medra_aaVoweldivesakuru.undera, na_medya_iVoweldivesakuru.undera, sa_medra_iiVoweldivesakuru.undera, ta_medra_uVoweldivesakuru.undera, ta_medya_halantadivesakuru.undera, ta_medya_iVoweldivesakuru.undera, ta_ta_medra_iVoweldivesakuru.undera, ta_tha_medra_iVoweldivesakuru.undera, va_medya_iVoweldivesakuru.undera, va_medya_uVoweldivesakuru.undera and ya_medya_iVoweldivesakuru.undera</p>
 [code: legacy-long-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifDivesAkuru/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, todhri, syriac, math, hebrew, canadian-aboriginal, tifinagh, coptic, malayalam, tai-le, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+11939 : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>dives-akuru</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Avokaya (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Dan (Latn, 1,099,244 speakers), Aghem (Latn, 38,843 speakers), Mfumte (Latn, 79,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kom (Latn, 360,685 speakers), Koonzime (Latn, 40,000 speakers), Gulay (Latn, 250,478 speakers), Ma’di (Latn, 584,000 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Mango (Latn, 77,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mundani (Latn, 34,000 speakers), Yala (Latn, 200,000 speakers), Cicipu (Latn, 44,000 speakers), Zapotec (Latn, 490,000 speakers), Bafut (Latn, 158,146 speakers), Dii (Latn, 71,000 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Vute (Latn, 21,000 speakers), Nateni (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Nzakara (Latn, 50,000 speakers), Lugbara (Latn, 2,200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Fur (Latn, 1,230,163 speakers), Makaa (Latn, 221,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* lla_ooVoweldivesakuru.undera: L&lt;&lt;1445.0,32.0&gt;--&lt;1446.0,32.0&gt;&gt; -&gt; L&lt;&lt;1446.0,32.0&gt;--&lt;1446.0,32.0&gt;&gt;

* lla_ooVoweldivesakuru: L&lt;&lt;1445.0,32.0&gt;--&lt;1446.0,32.0&gt;&gt; -&gt; L&lt;&lt;1446.0,32.0&gt;--&lt;1446.0,32.0&gt;&gt;

* u1190C_u1193D.0007: L&lt;&lt;804.0,473.0&gt;--&lt;804.0,473.0&gt;&gt; -&gt; L&lt;&lt;804.0,473.0&gt;--&lt;804.0,473.0&gt;&gt;

* u1192E_u11931.undera: L&lt;&lt;449.0,32.0&gt;--&lt;450.0,32.0&gt;&gt; -&gt; L&lt;&lt;450.0,32.0&gt;--&lt;450.0,32.0&gt;&gt;

* u1192E_u11931: L&lt;&lt;449.0,32.0&gt;--&lt;450.0,32.0&gt;&gt; -&gt; L&lt;&lt;450.0,32.0&gt;--&lt;450.0,32.0&gt;&gt;

* u1192E_u11932.undera: L&lt;&lt;449.0,32.0&gt;--&lt;450.0,32.0&gt;&gt; -&gt; L&lt;&lt;450.0,32.0&gt;--&lt;450.0,32.0&gt;&gt;

* u1192E_u11932: L&lt;&lt;449.0,32.0&gt;--&lt;450.0,32.0&gt;&gt; -&gt; L&lt;&lt;450.0,32.0&gt;--&lt;450.0,32.0&gt;&gt;

* u1192E_u11938.undera: L&lt;&lt;1095.0,32.0&gt;--&lt;1096.0,32.0&gt;&gt; -&gt; L&lt;&lt;1096.0,32.0&gt;--&lt;1096.0,32.0&gt;&gt;

* u1192E_u11938: L&lt;&lt;1095.0,32.0&gt;--&lt;1096.0,32.0&gt;&gt; -&gt; L&lt;&lt;1096.0,32.0&gt;--&lt;1096.0,32.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u11909.alt.undera: L&lt;&lt;753.0,127.0&gt;--&lt;754.0,127.0&gt;&gt;/B&lt;&lt;754.0,127.0&gt;-&lt;546.0,95.0&gt;-&lt;421.0,50.5&gt;&gt; = 8.746162262555211

* u11909.alt: L&lt;&lt;753.0,127.0&gt;--&lt;754.0,127.0&gt;&gt;/B&lt;&lt;754.0,127.0&gt;-&lt;546.0,95.0&gt;-&lt;421.0,50.5&gt;&gt; = 8.746162262555211

* u1190C_u1193D.0002: B&lt;&lt;1026.0,595.0&gt;-&lt;973.0,573.0&gt;-&lt;924.0,551.0&gt;&gt;/B&lt;&lt;924.0,551.0&gt;-&lt;962.0,559.0&gt;-&lt;993.0,559.0&gt;&gt; = 12.29044910706117

* u1190C_u1193D.0003: B&lt;&lt;1218.0,666.0&gt;-&lt;1066.0,611.0&gt;-&lt;932.0,550.0&gt;&gt;/B&lt;&lt;932.0,550.0&gt;-&lt;968.0,558.0&gt;-&lt;996.0,558.0&gt;&gt; = 11.947353801719451

* u1190C_u1193D.0004: B&lt;&lt;1111.0,624.0&gt;-&lt;1017.0,586.0&gt;-&lt;934.0,548.0&gt;&gt;/B&lt;&lt;934.0,548.0&gt;-&lt;971.0,556.0&gt;-&lt;1000.0,556.0&gt;&gt; = 12.399321877776666

* u1190C_u1193D.0005: B&lt;&lt;1152.5,629.5&gt;-&lt;1048.0,590.0&gt;-&lt;953.0,549.0&gt;&gt;/B&lt;&lt;953.0,549.0&gt;-&lt;980.0,554.0&gt;-&lt;1002.0,554.0&gt;&gt; = 12.852533949245883

* va_medya_iVoweldivesakuru.undera: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015

* va_medya_iVoweldivesakuru: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015

* va_medya_uVoweldivesakuru.undera: B&lt;&lt;1366.5,198.0&gt;-&lt;1331.0,142.0&gt;-&lt;1249.0,89.0&gt;&gt;/B&lt;&lt;1249.0,89.0&gt;-&lt;1348.0,129.0&gt;-&lt;1427.5,181.0&gt;&gt; = 10.875563401670016

* va_medya_uVoweldivesakuru.undera: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015

* va_medya_uVoweldivesakuru: B&lt;&lt;1366.5,198.0&gt;-&lt;1331.0,142.0&gt;-&lt;1249.0,89.0&gt;&gt;/B&lt;&lt;1249.0,89.0&gt;-&lt;1348.0,129.0&gt;-&lt;1427.5,181.0&gt;&gt; = 10.875563401670016

* va_medya_uVoweldivesakuru: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015

* va_medyadivesakuru.undera: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015

* va_medyadivesakuru: B&lt;&lt;792.5,200.0&gt;-&lt;749.0,138.0&gt;-&lt;677.0,94.0&gt;&gt;/B&lt;&lt;677.0,94.0&gt;-&lt;803.0,135.0&gt;-&lt;875.5,182.5&gt;&gt; = 13.404842093600015
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* u11944 (U+11944): L&lt;&lt;272.0,471.0&gt;--&lt;269.0,39.0&gt;&gt;

* u11944 (U+11944): L&lt;&lt;563.0,471.0&gt;--&lt;560.0,39.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.779x (1779)</p>
 [code: bad-hhea-range]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifDivesAkuru/googlefonts/ttf/NotoSerifDivesAkuru-Regular.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 6 | 14 | 116 | 6 | 109 | 0 | 
| 0% | 0% | 2% | 6% | 46% | 2% | 43% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
