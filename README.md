# 🏠 HomeTech

Un tema personalizzato e una dashboard YAML ottimizzata per smartphone, tutto in uno.

## 🎨 Tema

Percorso: `themes/hometech.yaml`  
Per attivarlo:
1. Copia il file in `/config/themes/` (oppure importa da HACS se supportato).
2. Abilita il tema nelle impostazioni di Home Assistant.

## 📱 Dashboard Smartphone

Percorso: `dashboards/smartphone.yaml`  
Per usarla:
1. Copia il file in `/config/dashboards/`.
2. Aggiungi al `configuration.yaml`:

```yaml
lovelace:
  mode: yaml
  dashboards:
    smartphone:
      mode: yaml
      title: Smartphone
      icon: mdi:cellphone
      show_in_sidebar: true
      filename: dashboards/smartphone.yaml
