# Csh-OkapiShell

MQM Scorecard Bitext Converter README

The following tool is a c# shell built around the Okapi Library using the Tikal tool to transform
TMX and XLIFF files into a bitext format for use in the MQM Scorecard tool. The converter currently
supports all .tmx files, .xlf files (v.1.2, not v2.0) and .sdlxliff files (from SDL Trados). The
converter will return the output file to the same directory where the original file was located.

To run the Program, launch the RunConverter.exe file. Upload the file you wish to be converted,
and enter in the locale codes for the desired source and target languages. Click convert and a
console window should open briefly. When the window closes, the conversion is complete.

BYU Translation Research Group 2018
