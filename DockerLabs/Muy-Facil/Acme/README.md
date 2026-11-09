# Acme - DockerLabs

## Creada por: mikisbd

##Información: 
- Maquina con acceso fácil al ssh donde después deberás explorar los servicios web interno e intentar explotarlo

## Información general

- Plataforma: DockerLabs
- Dificultad: Muy fácil
- Sistema operativo: Linux
- Fecha: 09/11/2026
- Estado: En progreso

## Verificación de conectividad

```
┌──(kali㉿kali)-[~/Documentos/DOCKER-LABS/acme]
└─$ ping 172.17.0.2
PING 172.17.0.2 (172.17.0.2) 56(84) bytes of data.
64 bytes from 172.17.0.2: icmp_seq=1 ttl=64 time=0.073 ms
64 bytes from 172.17.0.2: icmp_seq=2 ttl=64 time=0.051 ms
64 bytes from 172.17.0.2: icmp_seq=3 ttl=64 time=0.050 ms
64 bytes from 172.17.0.2: icmp_seq=4 ttl=64 time=0.041 ms
64 bytes from 172.17.0.2: icmp_seq=5 ttl=64 time=0.041 ms
64 bytes from 172.17.0.2: icmp_seq=6 ttl=64 time=0.047 ms
64 bytes from 172.17.0.2: icmp_seq=7 ttl=64 time=0.050 ms
64 bytes from 172.17.0.2: icmp_seq=8 ttl=64 time=0.045 ms
64 bytes from 172.17.0.2: icmp_seq=9 ttl=64 time=0.045 ms
^C
--- 172.17.0.2 ping statistics ---
9 packets transmitted, 9 received, 0% packet loss, time 8176ms
rtt min/avg/max/mdev = 0.041/0.049/0.073/0.009 ms
```

## 1. Reconocimiento

- Comando usado
```
┌──(kali㉿kali)-[~/Documentos/DOCKER-LABS/acme]
└─$ nmap -p- --open -sV -sC -n 172.17.0.2  
```
- Resultado
```
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8.9p1 Ubuntu 3ubuntu0.16 (Ubuntu Linux; protocol 2.0)
| ssh-hostkey: 
|   256 ae:8a:0a:ff:6e:ce:89:a3:31:d7:da:44:85:0d:f4:de (ECDSA)
|_  256 3f:e8:fa:07:33:e8:43:0a:22:1d:6d:15:a6:53:04:7e (ED25519)
80/tcp open  http    Apache httpd 2.4.52 ((Ubuntu))
| http-robots.txt: 1 disallowed entry 
|_/migration_notes.txt
|_http-server-header: Apache/2.4.52 (Ubuntu)
|_http-title: ACME Corporation - Portal en Mantenimiento
MAC Address: 3E:D2:54:47:26:C2 (Unknown)
Service Info: OS: Linux; CPE: cpe:/o:linux:linux_kernel
```
# 2. Enumeración

## 3. Análisis de vulnerabilidades

## 4. Explotación

## 5. Escalada de privilegios

## 6. Evidencias

## 7. Conocimientos adquiridos

## 8. Conclusión
