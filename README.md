# 💰 Calculadora_Dividas_Dom

**Aplicación de consola para convertir divisas al Peso Dominicano (DOP)** en tiempo casi real.  
Convierte fácilmente monedas extranjeras a pesos dominicanos utilizando tasas de cambio actualizadas desde internet.  
Si no hay conexión, la app usa automáticamente la última tasa guardada localmente.

---

## 🚀 Características

- 🌎 Conversión de múltiples monedas extranjeras a DOP.  
- 🔍 Verificación automática de conexión a internet.  
- 💾 Uso de tasas guardadas localmente si no hay conexión.  
- ⚡ Interfaz por consola, rápida y ligera.  
- 🧩 Código modular y fácil de mantener.  

---

## 🛠️ Tecnologías utilizadas

**Lenguaje:** Python 3.10+  

**Librerías principales:**
- `requests` → Obtiene tasas desde una API.
- `json` → Guarda y lee tasas locales.
- `os` / `socket` → Verifica conexión a internet.

---

## 📦 Instalación

```bash
git clone https://github.com/tu_usuario/Calculadora_Dividas_Dom.git
cd Calculadora_Dividas_Dom
pip install -r requirements.txt
