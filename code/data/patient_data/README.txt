This subdirectory contains all the necessary data files to run the script. The included data are invented data for demonstration purposes only.

"nicolet_file_times.xlsx" described the Nicolet file recording time data and contained the following columns: "FIS" (with entries as strings such as FIS1), "fis_num" (with entries as integers such as 1), "folder_path" (the path to the folder containing the downloaded FIS file), "date_cx" (the date of the surgeries, expressed as DDMMYYYY), "analyze_end_time" (the time that the surgery ended, expressed as HHMM), "recording_start_date" (the date the recording started, expressed as DDMMYYYY), "recording_start_time" (expressed as HHMMSS), and "recording_time_total" (expressed as HHMMSS).


"OBM_file_times.xlsx" described the OBM file recording time data and contained the following columns: "folder_path" (the path to the folder containing the downloaded FIS file), "recording_start_date" (the date the recording started, expressed as DDMMYYY), and "recording_start_time" (expressed as HHMMSS).


"surgery_time_data.xlsx" described important surgical time points and contained the following columns: "fis_num" (with entries as integers such as 1), "date_surgery" (with entries as dates formatted as 1900-04-16), "time_start_cx" (with entries as surgery start times formatted as HHMM), "time_end_cx" (with entries as surgery end times formatted as HHMM), "time_start_ecc" (with entries as the start of CPB formatted as HHMM), "time_start_clamp" (with entries as the start of aortic cross clamping formatted as HHMM), "time_end_clamp" (with entries as the end of aortic cross-clamping formatted as HHMM), and "time_end_ecc" (with entries as the end of CPB formatted as HHMM).


NB: The code was neither been built for nor validated on surgeries ocurring during two different calendar days (i.e., starting at 2300 on Jan 1 and ending at 0100 on Jan 2).
