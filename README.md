2026-04-09
- Adjusted PLC and HMI files to include 2 new cameras (Camera CTRL routines, Cycle_Inspection, Cycle_Inspection_HMI, ProcessTasks, Rabbit)
- Updated all cycle routines 1st rung to use AutoCycle in place of InCycle
- Updated all CycleXXX_HMI routines SFS rung 



2026-04-06
- Made minor improvements from the Lower PLC file
- Removed unused UDTs


2026-04-02
- Removed the ConvBlocked logic I was testing.  Not required.


2026-03-31
- Updated HMI_Display routines.  Typos, spelling.
- Adjusted Keyence lasers y-axis
    - LN1 13001 -1.5mm in y
    - LN1 13101 -1.5mm in y
    - LN2 13001 -3mm in y
    - LN2 13101 -3mm in y
    - LN3 13001 -2.5mm in y
    - LN3 13101 -3mm in y


2026-03-30
- Made minor changes to simplify / clean up logic (changes suggested from Lower PLC file)
- Made backups of Lane 3 cameras that have SCALING and put our pixel programs back in before the System run.


2026-03-30
- Loaded backups from local storage




