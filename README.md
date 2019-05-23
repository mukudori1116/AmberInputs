# AmberInputs
## 1. Energy minimize
* 200 steps steepest descent
* 200 steps conjugate gradient

## 2. NVT
### Heat protein and solvent system
* 100 ps
* Heat the system from 0 to 300 K
* Restrain complex

## 3. NPT1
### Constant pressure system with restrain
* 50 ps
* 1 atm
* Restrain complex

## 4. NPT2
### Constant pressure system
* 50 ps
* 1 atm
* **No restrain**

## 5. Production run
### MD simulation
* 5 ns
* Output every 10 ps
