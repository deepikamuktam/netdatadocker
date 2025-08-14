# netdatadocker

step-1 : install netdata container on docker & run it

docker run -d --name=netdata \
  -p 19999:19999 \
  --cap-add SYS_PTRACE \
  --security-opt apparmor=unconfined \
  netdata/netdata

step-2 : Once it’s running, open netdata

http://localhost:19999

screenshots:

<img width="1802" height="518" alt="system_cpu" src="https://github.com/user-attachments/assets/364624fb-7c0b-4a06-bceb-7464922d021c" />

<img width="1802" height="518" alt="app_disk_logical_io" src="https://github.com/user-attachments/assets/fd2bc959-f07b-4e78-9c8e-2972a96fe304" />

<img width="1909" height="1011" alt="Screenshot 2025-08-14 105517" src="https://github.com/user-attachments/assets/9b3e1d7d-a668-4cbf-acbc-e2833b64f4dd" />

<img width="1919" height="1010" alt="Screenshot 2025-08-14 104603" src="https://github.com/user-attachments/assets/d2e8fbdc-b122-481f-9435-3a534d776f2d" />








