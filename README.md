# GCV0-File-Processor
This is the application that is used to process CSV files.

This command has been used to split one zip file of app into two zip files:
zip "GCV0 File Processor v1.0.zip" --out "GCV0 File Processor v1.0.zip" -s 25m


Use following to merge the two files back into one zip file:
zip -s0 "GCV0 File Processor v1.0.zip" --out "out/GCV0 File Processor v1.0.zip"
