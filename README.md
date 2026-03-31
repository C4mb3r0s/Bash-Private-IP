<div align="center">

# 🌐 ipPrivadaScan

<img src="https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white"/>
<img src="https://img.shields.io/badge/Platform-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>

**Script minimalista en Bash para obtener tu dirección IP privada de forma rápida y con estilo.**

</div>

---

### 📸 Preview

```
[+] Esta es tu dirección IP Privada -> 192.168.1.105
```

---

## ⚡ Características

- 🎨 Salida con colores ANSI para mejor legibilidad
- 🔍 Detección automática de la IP de la interfaz inalámbrica (`wlp1s0`)
- 🪶 Ligero y sin dependencias externas más allá de `ip` y `awk`

---

## 🚀 Uso

```bash
git clone https://github.com/C4mber0s/ipPrivadaScan.git
cd ipPrivadaScan
chmod +x privateIp.sh
./privateIp.sh
```

---

## 🛠️ Requisitos

| Herramienta | Descripción |
|-------------|-------------|
| `bash`      | Intérprete de shell |
| `iproute2`  | Proporciona el comando `ip` |
| `awk`       | Procesamiento de texto |

> ⚠️ **Nota:** El script detecta la interfaz `wlp1s0`. Si tu interfaz tiene un nombre diferente, edita la línea 13 del script y reemplaza `wlp1s0` por el nombre correspondiente (ej. `wlan0`, `eth0`).

---

## 📁 Estructura

```
ipPrivadaScan/
└── privateIp.sh   # Script principal
```

---

## 👤 Autor

<div align="center">

**Eduardo Camberos**

[![GitHub](https://img.shields.io/badge/GitHub-C4mb3r0s-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/C4mb3r0s)

</div>
