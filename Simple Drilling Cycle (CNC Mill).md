<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h2>🧾 Sample 2: Simple Drilling Cycle (CNC Mill)</h2>
  <p><strong>Objective:</strong> Drill 4 holes in a 40x40 mm square layout.</p>

  <div class="gcode-container">
%<br>
O0102 (Drilling 4 Holes)<br>
G21 G17 G90 G40 G49 G80<br>
T02 M06 (Drill Bit)<br>
G00 G54 X-20 Y-20<br>
G43 Z50 H02<br>
M03 S1200<br>
G81 R2 Z-10 F75<br>
X20 Y-20<br>
X20 Y20<br>
X-20 Y20<br>
G80<br>
G00 Z50<br>
M05<br>
M30<br>
%<br>
  </div>

</body>
</html>
