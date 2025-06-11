<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h2>🧾 Sample 3: CNC Lathe Turning Cycle (OD Turning)</h2>
  <p><strong>Objective:</strong> Turn an OD from Ø40mm to Ø30mm over 100mm length.</p>

  <div class="gcode-container">
%<br>
O0103 (OD Turning)<br>
G21 G18 G90 G40 G99<br>
T0101 (Roughing Tool)<br>
G00 X42 Z2<br>
G96 S200 M03<br>
G01 Z0 F0.2<br>
X30<br>
Z-100<br>
X42<br>
G00 Z2<br>
M05<br>
M30<br>
%<br>
  </div>

</body>
</html>
