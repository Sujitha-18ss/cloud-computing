 mkdir hrms_server
  753  cd hrms_server
  754  mkdir Employee_Records Payroll Leave_Management Training
  755  cd Employee_Records
  756  cd Employee_data
  757  touch Employee_data
  758  cd Employee_data
  759  nano Employee_data
  760  cd ..
  761  cd Payroll
  762  touch Emp_salary
  763  touch Emp_payslip
  764  cd ..
  765  cd Leave_Management
  766  touch Leave_records
  767  cd ..
  768  cd Training
  769  touch Schedules
  770  cd ..
  771  cd Employee_data
  772  cd Employee_Records
  773  touch emp_01
  774  touch emp_02 emp_03
  775  cd ..
  776  mkdir Archived_Payslips
  777  mv Emp_payslip /home/skacas/Desktop/hrms_server/Archived_Payslips
  778  cd Payroll
  779  mv Emp_payslip /home/skacas/Desktop/hrms_server/Archived_Payslips
  780  cd ..
  781  cd Employee_Records
  782  mv Employee_data Emp_data_2024
  783  cd ..
  784  ls
  785  ls -al
  786  touch sensitive_employee_data.xlsx
  787  nano sensitive_employee_data.xlsx
  788  chmod 755 sensitive_employee_data.xlsx #owner:rwx,group:---,others:---
  789  ls -al
  790  mkdir Backup
  791  cp Employee_Records Backup
  792  cp -r Employee_Records Backup
  793  cp -r Payroll Backup
  794  cd Backup
  795  ls -al
  796  cd ..
  797  cd Employee_Records
  798  rm emp_03
  799  nano emp_03 emp_04 emp_05 emp_06 emp_07 emp_07 emp_08 emp_09 emp_10
  800  nano emp_01 emp_02
  801  cd ..
  802  history
  803  history | grep payroll
  804  history | grep "emp"
  805  uptime
  806  ls -al
  807  ping google.com
  808  grep "emp_07"
  809  grep "emp_07"Employee_Records
  810  grep -r "emp_07"Employee_Records
  811  grep -r "emp_07" Employee_Records
  812  grep -r "emp" Employee_Records
  813  grep -r "ss" Employee_Records
  814  cd
  815  mkdir hr_manager1
  816  cd hr_manager1
  817  touch records
  818  cd ..
  819  cd hr_manager2
  820  mkdir hr_manager2
  821  cd hr_manager2
  822  touch records
  823  cd ..
  824  ls
  825  ls -al
  826  df -h
  827  cd Desktop
  828  cd hrms_server
  829  ls -al
  830  find . -empty -type d -delete
  831  ls -al
  832  rm Leave_records
  833  find . -empty -type d -delete
  834  ls -al
  835  cd ..
  836  sort hrms_server
  837  sort -r hrms_server
  838  cd hrms_server
  839  sort Employee_Records
  840  cd Employee_Records
  841  ls -lS
  842  cd ..
  843  ls -al
  844  find . -type f -name "*.xlsx"
  845  tar -cvf Employee_Records.tar.gz
  846  touch archive
  847  tar -cvf Employee_Records.tar.gz
  848  tar cvzf tarball.tar.gz Employee_Records
  849  history
