# ha-nordpool-graph
Nordpool DK2 setup and graph for sale of DK2 power

For my solar setup, I have a raw nordpool price and graph available 

<img width="502" alt="Screenshot 2025-04-11 at 17 27 00" src="https://github.com/user-attachments/assets/f6f80bde-2de2-409e-b03c-b41322d3d626" />

1) Install ApexCard, Nordpool, cheapest-energy-hours and HACS if needed, https://github.com/RomRider/apexcharts-card && http://hacs.xyz && https://github.com/custom-components/nordpool && https://github.com/TheFes/cheapest-energy-hours
2) 
3) Add card with this https://github.com/peterczarlarsen-ha/ha-nordpool-graph/blob/main/apexcharts.yaml
4) wee need two helpers for tomorrow min and max, we add this below
5) Add a "template sensor", settings -> devices and services -> Helpers, for tomorrow min: https://github.com/peterczarlarsen-ha/ha-nordpool-graph/blob/main/nordpool_tomorrow_min.yaml
<img width="606" alt="Screenshot 2025-04-11 at 17 42 10" src="https://github.com/user-attachments/assets/44710335-5708-453c-a28e-b961e8d8509c" />
   
