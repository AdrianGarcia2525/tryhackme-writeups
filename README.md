# TryHackMe Writeups

Documentación técnica de máquinas resueltas en TryHackMe, organizadas por superficie de ataque. El objetivo de este repositorio no es coleccionar soluciones, sino mostrar metodología: cómo enumero, cómo razono el vector de entrada, cómo escalo privilegios y qué aprendo de cada máquina.

📌 **Perfil de TryHackMe:** https://tryhackme.com/p/EniGma
📌 **Portafolio:** [tu-web.com](https://tu-web.com)

---

## 🗂️ Índice por categoría

### Active Directory
| Máquina | Dificultad | Vector de entrada | Escalada | Writeup |
|---|---|---|---|---|
| Attacktive Directory | Fácil | Kerberoasting | AS-REP Roasting | [Ver](./active-directory/attacktive-directory) |

### Windows Exploitation
| Máquina | Dificultad | Vector de entrada | Escalada | Writeup |
|---|---|---|---|---|
| Blue | Fácil | EternalBlue (MS17-010) | SYSTEM vía exploit | [Ver](./windows-exploitation/blue) |

### Web Exploitation
| Máquina | Dificultad | Vector de entrada | Escalada | Writeup |
|---|---|---|---|---|
| Vulnversity | Fácil | File upload bypass | Binario SUID | [Ver](./web-exploitation/vulnversity) |

### Linux Exploitation
| Máquina | Dificultad | Vector de entrada | Escalada | Writeup |
|---|---|---|---|---|
| Kenobi | Fácil | SMB anónimo | Binario mal configurado | [Ver](./linux-exploitation/kenobi) |

### Network Services
| Máquina | Dificultad | Vector de entrada | Escalada | Writeup |
|---|---|---|---|---|
| ... | ... | ... | ... | [Ver](./network-services/...) |

### Binary Exploitation
| Máquina | Dificultad | Vector de entrada | Escalada | Writeup |
|---|---|---|---|---|
| ... | ... | ... | ... | [Ver](./binary-exploitation/...) |

---

## 🛠️ Metodología general

Cada writeup sigue esta estructura:
1. **Reconocimiento** — escaneo de puertos y servicios (nmap, etc.)
2. **Enumeración** — identificación de vectores de ataque
3. **Explotación** — obtención de acceso inicial
4. **Escalada de privilegios** — de usuario a root/administrador
5. **Lecciones aprendidas** — mitigación y takeaways técnicos

## 📈 Progreso

- Máquinas completadas: X
- Categorías cubiertas: Active Directory, Windows Exploitation, Web Exploitation, Linux Exploitation

## ⚠️ Nota

Los writeups asumen que el lector ya tiene acceso a la máquina correspondiente en TryHackMe. No se comparten flags completas ni contenido que viole los términos de la plataforma.

---

📫 Contacto: [adrigarcia1315@gmail.com] · [LinkedIn](https://linkedin.com/in/tu-perfil)
