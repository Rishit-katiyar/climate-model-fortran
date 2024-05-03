# Command List

1. **Clone Repository**: 
   ```bash
   git clone https://github.com/Rishit-katiyar/climate-model-fortran.git
   ```

2. **Navigate to Repository Directory**: 
   ```bash
   cd climate-model-fortran
   ```

3. **Compile Fortran Code**: 
   ```bash
   gfortran climate_model.f90 -o climate_model
   ```

4. **Run Model**: 
   ```bash
   ./climate_model
   ```

5. **Check Fortran Compiler Version**:
   ```bash
   gfortran --version
   ```

6. **Check System Environment**:
   ```bash
   uname -a
   ```

7. **Check Available Memory**: 
   ```bash
   free -h
   ```

8. **Check Disk Space**: 
   ```bash
   df -h
   ```

9. **Check CPU Usage**: 
   ```bash
   top
   ```

10. **Check System Logs for Errors**: 
    ```bash
    dmesg | grep error
    ```

11. **Check Compiler Options**: 
    ```bash
    gfortran -Q --help=optimizers
    ```

12. **Check Runtime Diagnostics**: 
    ```bash
    tail -n 1000 climate_model.log
    ```

13. **Enable Debugging Output**: 
    ```bash
    sed -i 's/DEBUG = .FALSE./DEBUG = .TRUE./g' climate_model.f90
    ```

14. **Check Dependencies**: 
    ```bash
    ldd ./climate_model
    ```

15. **Check Library Versions**: 
    ```bash
    ldconfig -p | grep <library_name>
    ```

16. **Check Environmental Variables**: 
    ```bash
    printenv
    ```
