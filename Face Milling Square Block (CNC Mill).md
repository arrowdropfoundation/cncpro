<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h2>🧾 Sample 1: Face Milling Square Block (CNC Mill)</h2>
  <p><strong>Objective:</strong> Face a 50x50 mm square surface starting from the center.</p>

  <div class="gcode-container">
%<br>
O0101 (Face Milling)<br>
G21 G17 G90 G40 G49 G80<br>
T01 M06 (Tool change to T1 - Face Mill)<br>
G00 G54 X0 Y0<br>
G43 Z50 H01<br>
M03 S1500<br>
G00 Z5<br>
G01 Z-1.0 F100<br>
X-25 Y-25<br>
X25<br>
Y25<br>
X-25<br>
Y-25<br>
G00 Z50<br>
M05<br>
M30<br>
%<br>
  </div>

</body>
</html>
