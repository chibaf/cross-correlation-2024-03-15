# cross-correlation-2024-03-15
cross correlation of fluid near froze wall

f1=Fourier[a1]

f2=Conjugate[Fourier[a2]]

ff=f1*f2

c1 = Re[InverseFourier[ff]]/(Norm[a1] Norm[a2]);


