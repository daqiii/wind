# wind
DESI telemetry - wind analysis
The logs2constraints extracts NFS AZ and EL constraints from the OCS log files. It uses the performance_night telemetry table 
to get dusk and dawn times to reset the constraints
The resulting data is available in the csv and pkl files with the columns obsday, time_recorded, dusk, dawn
