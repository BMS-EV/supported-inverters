# Supported Hybrid Inverters

Public database of **56 hybrid inverter models** compatible with second-life EV batteries via [BMS-EV](https://bms-ev.com/) controllers.

**Full documentation:** [docs.bms-ev.com/inverters/](https://docs.bms-ev.com/inverters/)  
**Interactive matrix:** [docs.bms-ev.com/compatibility/](https://docs.bms-ev.com/compatibility/)

## Data

- [inverters.csv](inverters.csv) — machine-readable list of all 56 supported hybrid inverter models with count of compatible batteries per inverter

## By manufacturer

| Manufacturer | Series | DC voltage range | Documentation |
|-------------|--------|------------------|---------------|
| **Deye** | SUN-(5-20)K HP3 AM2 (single-phase), SUN-(29.9-50)K HP3 BM3 (three-phase) | 160-800V | [Deye](https://docs.bms-ev.com/inverters/deye/) |
| **SOFAR** | HYD 5-20KTL-3PH | 350-800V | [SOFAR](https://docs.bms-ev.com/inverters/sofar/) |
| **GoodWe** | EH (single-phase), ET (three-phase), ES, EHB, BH, BT, A-ES Split Phase | 40-600V (varies by series) | [GoodWe](https://docs.bms-ev.com/inverters/goodwe/) |
| **SolaX** | X1 Hybrid, X1 Hybrid G4, X3 Hybrid, X3 Hybrid G4, X3-Ultra | 48V LV or 90-800V HV | [SolaX](https://docs.bms-ev.com/inverters/solax/) |
| **SMA** | Sunny Boy Storage 2.5/3.7/5.0/6.0, Sunny Boy Smart Energy 3.6-6.0, Sunny Tripower X, Sunny Tripower Smart Energy | 48V or 100-500V HV | [SMA](https://docs.bms-ev.com/inverters/sma/) |
| **Fronius** | Primo Gen24 Plus, Symo Gen24 Plus, Symo Hybrid 3.0/4.0/5.0-3-S, Verto Plus 15-33kW | 150-800V | [Fronius](https://docs.bms-ev.com/inverters/fronius/) |
| **Sungrow** | SH RS/RT/T series | 80-800V | [Sungrow](https://docs.bms-ev.com/inverters/sungrow/) |
| **Solis** | RHI-3P HVES-5G, S5-EH1P, S6-EH1P/EH3P | 90-800V | [Solis](https://docs.bms-ev.com/inverters/solis/) |
| **FoxESS** | H1/AC1, H3/AC3, H3 Smart, H3 Pro | 90-600V | [FoxESS](https://docs.bms-ev.com/inverters/foxess/) |
| **Kostal** | Plenticore Plus 3.0-10 | 120-720V | [docs](https://docs.bms-ev.com/inverters/) |
| **Growatt** | SPH LV/HV series, WIT 50-100K-HU | 48V LV or 100-500V HV | [docs](https://docs.bms-ev.com/inverters/) |
| **SAJ** | H2 Hybrid (3-12)K-S2 | 100-500V | [docs](https://docs.bms-ev.com/inverters/) |
| **Huawei** | SUN2000-(2-6)KTL-L1 400V, SUN2000-(3-20)K-MB0 400V | 100-500V | [docs](https://docs.bms-ev.com/inverters/) |
| **Hoymiles** | HYT/HAT-HV | — | [docs](https://docs.bms-ev.com/inverters/) |
| **Felicity** | T-REX-50KHP3G01 | — | [docs](https://docs.bms-ev.com/inverters/) |
| **Ferroamp** | EnergyHub | 800V-capable | [docs](https://docs.bms-ev.com/inverters/) |
| **Afore** | AF17K-THA 230V | — | [docs](https://docs.bms-ev.com/inverters/) |

## Communication protocols

BMS-EV translates between the vehicle's original BMS and the inverter's expected CAN protocol:

- **Pylontech-derived** — Deye, Growatt, most Chinese hybrid inverters
- **BYD Battery-Box HVS** — SOFAR HYD, GoodWe EH/ET, Fronius, some SolaX
- **SolaX native** — X1/X3 Hybrid G4 series
- **SMA BAT-CAN** — SMA Sunny Boy/Tripower Smart Energy
- **Sungrow SBH/SBR** — Sungrow SH series (with Pylontech fallback)
- **KOSTAL Smart Battery** — Kostal Plenticore Plus
- **Fronius Solar Battery** — BYD-compatible

## Compatibility Matrix

Full **72 batteries × 56 inverters** matrix: https://docs.bms-ev.com/compatibility/

Machine-readable: [supported-batteries](https://github.com/BMS-EV/supported-batteries) · [full compatibility CSV](https://github.com/BMS-EV/bms-ev-docs/blob/main/compatibility.csv)

## How to contribute

Missing an inverter? Have you successfully installed one that isn't listed? [Open an issue](https://github.com/BMS-EV/supported-inverters/issues) with details.

## License

[MIT License](LICENSE)

## Contact

- Shop: https://bms-ev.com/
- Documentation: https://docs.bms-ev.com/
- Email: office@bms-ev.com
