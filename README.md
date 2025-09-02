# Sysvinit-2.98-Static-build-arm
Di linux, kernel diberi id proses dengan 0<br/><br/>sedangkan id proses 1 diberi untuk init proses<br/>banyak metode init di distro linux.<br/>misalnya: systemd, openRc, busybox init dll.<br/><br/><h2>Pada Sysv init</h2><br/>saat perangkat linux dinyalakan, init akan diberi PID 1, init akan menelurkan proses lainnya sampai level tertentu agar sistem berjalan.<br/>Di perangkat tertanam, init menjalankan /etc/inittab lalu menjalankan default di /etc/init.d/rcS<br/>Di Android juga menggunakan init,<br/>init di Android menjalankan skrip /init.*.rc utamanya ada di /init.rc<br/>Tangkapan layar init static build di Router usb mdm9607.<br/>
<center>
  <img width="70%" height="70%" src="https://raw.githubusercontent.com/jendraljack/Sysvinit-2.98-Static-build-arm/refs/heads/main/tangkapanLayar/ss1.jpeg"></img>
</center>
