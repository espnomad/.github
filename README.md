<p align="center">
  <img src="https://raw.githubusercontent.com/espnomad/.github/main/files/espnomad_logo%404x.png" alt="ESPnomad Logo" width="200"/>
</p>


# ESPnomad

**Modular ESPHome-based automation for 12V, 24V, and 48V mobile systems**  
*For campervans, RVs, boats, off-grid homes, and mobile labs.*

---

## 🧭 What is ESPnomad?

**ESPnomad** is an open-source ecosystem based on [ESPHome](https://esphome.io/) tailored for **movable homes and off-grid setups**.  
It’s designed to bring the power and flexibility of smart home automation to the **nomadic lifestyle** — think **campervans, RVs, boats, tiny houses, expedition trucks, mobile labs**, and **off-grid cabins**.

Whereas ESPHome focuses on fixed buildings, **ESPnomad brings the smart home on the road**.

---

## ⚡ Key Features

- 🔌 **Supports 12V / 24V / 48V DC systems**  
  Designed to integrate cleanly into mobile electrical systems, respecting power constraints and safety.

- 🔋 **Connects with EMS / BMS / MPPT systems**  
  Interfaces with a variety of power components from brands like Renogy, Victron, Daly, JK, and more.

- 🧩 **Modular and composable**  
  Each module (shunt readers, tank sensors, diesel heater controls, inverter toggles, etc.) can work standalone or in concert.

- 🌐 **Native Home Assistant integration**  
  Use ESPHome’s full potential to bring your entire vehicle or vessel into your smart dashboard.

- 🛠️ **Built for DIYers**  
  Schematic files, 3D printable cases, firmware configs, and board designs — all open and ready to be customized.

- 🌍 **Off-grid ready**  
  Power-efficient designs, battery monitoring, remote diagnostics, and system safety all prioritized for remote environments.

---

## 🔧 Use Cases

- Smart **fuse boxes** with real-time current monitoring  
- **Diesel heater** integration (UART sniffing, control + diagnostics)  
- **Battery shunt modules**  
- **Water tank level sensors** 
- **Inverter controllers** (Renogy, Victron, etc.)  
- **Solar charge controller readouts** via Modbus/CAN 
- **ESPHome-based dashboards** in the cloud or local HA
- **Led light controllers**
- **Relay boards**
- **Ventilation controller**
- ... and many more in active development

---

## 🚐 Why ESPnomad?

Traditional home automation tools often fail when used in **mobile or off-grid contexts**:

- Vehicle power systems differ fundamentally from house wiring.
- Nomadic users often require **higher modularity**, **lower idle power draw**, and **manual overrides**.
- Systems must be **resilient**, **field-repairable**, and **understandable by the owner**.

**ESPnomad bridges that gap.**

---

## 👤 About the Creator

**ESPnomad** is created and maintained by **Toon**, a Belgian developer, maker, and vanlifer with a passion for robust, self-built systems.

As a developer and builder with a background in electronics, van conversion, and software, Toon found that existing solutions for **campervan automation** were fragmented, brand-locked, or not compatible with Home Assistant. There were expensive domotica systems on the market, but none that combined **simplicity, openness, and modularity** — especially for 12V, 24V, and 48V platforms.

So he started **ESPnomad** — a project that brings the power of ESPHome to life on the road.

Toon lives **part-time** in his self-converted Peugeot Boxer, powered by a 400Ah Renogy battery bank with a 50A DC-DC MPPT charger, Victron 15A AC charger, 2kW diesel heater, 85W floor heating, and ESPHome-based air quality sensors. He’s already integrated his Renogy inverter, charger (via Modbus), 500A smart shunt, IR-controlled Maxxfan, and more. His van is a lab on wheels — a working prototype of the ESPnomad system.

His goal: to make ESPnomad a **professional, compact, plug-and-play automation platform** for DIY builders, vanlifers, and anyone off the grid.

---

## 🤝 Get Involved

We welcome:

- Developers building ESPhome integrations
- Hardware tinkerers building camper/boat/tiny house systems
- Testers and vanlifers who want to field-test modules
- Van builders

Check out the [projects](https://github.com/orgs/espnomad/projects) and [issues](https://github.com/orgs/espnomad/issues), or start a discussion!

---

## 📦 Project Structure

This is the **meta-repo** for the organization.

You'll find:

- `espnomad/.github` – README, contributing guidelines, issue templates
- Other repositories will contain:
  - Hardware board documentation
  - ESPHome YAML configs for each module
  - Arduino firmware where needed
  - Example Home Assistant dashboards and Lovelace cards

---

## 🛠️ Licensing

ESPnomad is open-source. Individual projects may use MIT, GPLv3, or similar licenses.  
Please refer to the specific license in each repository.

---

## 🙏 Credits & Inspiration

ESPnomad stands on the shoulders of giants:  
- [ESPHome](https://esphome.io/)  
- [Home Assistant](https://www.home-assistant.io/)  
- The incredible work of the DIY camper/vanlife/maker community

---

## 📡 Stay Connected

More to come soon — Discord, website, and community hub.  
For now, star the repo and follow along.  
We’re just getting started.

> 🧭 Home is not a place — it's a system that moves with you.
