# Capacitance 2

Class: Physics
Created: Nov 12, 2020 9:45 AM
Sub-unit: Capacitors
Type: Notes
Unit(s): Particles and Medical Physics

Continuing from [Capacitence](Capacitence%205750e1bafc774a4b9bb66d284e635e12.md)

### When is a capacitor "discharged"

$V=V_0e^{-t/RC}\\V=V_0e^{-RC/RC}=V_0/e\approx 0.37V_0$ ← RC (Time constant) is the time it take to get to 0.37 of itself

The standard for discharge is when $t\approx(5,6)RC$

### Q's

1.

    $V=V_0/2=V_0e^{-600/RC}\\0.5=e^{-600/RC}\\ln(0.5)=-600/RC\rArr RC=-600/ln(0.5)=865.61$

    $RC=865\rArr R=865/100mF=8600\Omega$

### Turning it into a straight line

$V=V_0e^{-t/RC}\rArr ln(V)={-1\over RC}t+ln(V_0)$

Fits $y=mx+c$ where $y=ln(V), m={-1\over RC},c=ln(V_0)$

![[Capacitance 2/Untitled.png]]

### Discharge equations

$V_0=V_r+V_r$

At fully charged capacitor: $V_r=0, V_c=V_0$

$I=I_0e^{-t\over RC}$

$V_0=V_c+V_r=IR+V_c=I_0Re^{-t\over RC}+V_c\\=V_0e^{-t\over RC}+V_c\rArr V_c=V_0-V_0e^{-t\over RC}$
