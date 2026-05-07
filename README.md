<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0a0c10,1e2535,3b82f6&height=180&section=header&text=Daniel%20Aron&fontSize=42&fontColor=c8d0e0&fontAlignY=38&desc=Network%20Analyst%20%7C%20Infrastructure%20Automation&descAlignY=58&descColor=4a5568"/>

</div>

```python
class Daniel:
    def __init__(self):
        self.localização    = "Igarapé, MG 🇧🇧"
        self.foco           = ["Redes", "Automação", "Monitoramento"]
        self.ferramentas    = ["Zabbix", "Python", "Bash", "Linux"]
        self.horário_pico   = "23:00 – 03:00 ☕"
        self.filosofia      = "Sem saber que era impossível, eu fui lá e soube."

    def status(self):
        return "Quebrando cabeça com algo que vai virar automação amanhã"
```

---

## o que eu faço de verdade

Analista de redes que não aguentou ficar fazendo as coisas na mão. A maior parte do que eu construo nasce de um problema real que eu tive que resolver — e quando resolvo, automatizo pra nunca mais precisar fazer de novo.

Trabalho principalmente com **Zabbix**, infraestrutura de redes, e qualquer coisa que possa ser scripitada, monitorada ou transformada em dashboard.

---

## 🗺️ NetMap — Zabbix Topology Viewer

> O projeto que começou com *"quero ver minha rede num mapa"* e virou uma ferramenta de topologia completa.

**HTML/JS puro. Zero dependências. Roda em qualquer servidor.**

- Cadastro manual de hosts e conexões com busca de interfaces direto na API do Zabbix
- **Descoberta automática** de topologia MPLS — busca todos os hosts, correlaciona interfaces pelo nome da descrição e gera o mapa
- Linhas paralelas com animação de tráfego em tempo real (sent ↑ recv ↓)
- Cor varia de 🟢 verde → 🟠 laranja conforme a utilização (0–60% / 60–100%)
- 🟣 Roxo quando há discard ou erro na interface
- 🔴 Vermelho quando a interface está down — sem animação porque não tem tráfego
- Zoom, pan, waypoints customizáveis por conexão
- Atualização via API a cada 5 minutos com fallback automático entre hosts
- Estado salvo no servidor via PHP — todo mundo vê o mesmo mapa

[![NetMap](https://img.shields.io/badge/Ver%20Repositório-0a0c10?style=for-the-badge&logo=github&logoColor=3b82f6)]([[https://github.com/aron-dan/netmap](https://github.com/aron-dan/NetMap.git)](https://github.com/aron-dan/NetMap.git))

---

## stack que eu realmente uso

<div align="center">

![Python](https://img.shields.io/badge/Python-0a0c10?style=for-the-badge&logo=python&logoColor=3b82f6)
![Bash](https://img.shields.io/badge/Bash-0a0c10?style=for-the-badge&logo=gnu-bash&logoColor=3b82f6)
![JavaScript](https://img.shields.io/badge/JavaScript-0a0c10?style=for-the-badge&logo=javascript&logoColor=f7df1e)
![Linux](https://img.shields.io/badge/Linux-0a0c10?style=for-the-badge&logo=linux&logoColor=c8d0e0)
![Zabbix](https://img.shields.io/badge/Zabbix-0a0c10?style=for-the-badge&logo=zabbix&logoColor=cc2936)
![Apache](https://img.shields.io/badge/Apache-0a0c10?style=for-the-badge&logo=apache&logoColor=3b82f6)
![Git](https://img.shields.io/badge/Git-0a0c10?style=for-the-badge&logo=git&logoColor=f05032)
![Docker](https://img.shields.io/badge/Docker-0a0c10?style=for-the-badge&logo=docker&logoColor=2496ed)

</div>

---

## stats

<div align="center">

<img height="160em" src="https://github-readme-stats.vercel.app/api?username=aron-dan&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0a0c10&title_color=3b82f6&icon_color=3b82f6&text_color=c8d0e0"/>
<img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aron-dan&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&bg_color=0a0c10&title_color=3b82f6&text_color=c8d0e0"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=aron-dan&theme=tokyonight&hide_border=true&background=0a0c10&stroke=1e2535&ring=3b82f6&fire=f97316&currStreakLabel=c8d0e0)](https://git.io/streak-stats)

</div>

---

## 🏅 certificação

- **Zabbix Certified Professional** — porque monitorar sem entender o que você tá monitorando não é monitorar, é torcer

---

<div align="center">

```
se chegou até aqui, provavelmente é porque também fica
debugando coisa às 2 da manhã com café frio na mesa.
bem vindo ao clube.
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0a0c10,1e2535,3b82f6&height=100&section=footer"/>

</div>
