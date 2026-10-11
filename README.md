# security-scripts

> Scripts **Python** pequenos e práticos para suporte, NOC e SOC.

![Status](https://img.shields.io/badge/status-em%20constru%C3%A7%C3%A3o-yellow?style=flat-square) ![Python](https://img.shields.io/badge/Python-3.x-0d1117?style=flat-square&logo=python&logoColor=3ddc97)

## Scripts

| Script | O que faz | Status |
|---|---|---|
| `log_failed_logins.py` | Conta tentativas de login falhas por IP no `auth.log` | planejado |
| `port_check.py` | Verifica se portas/serviços de uma lista de hosts respondem | planejado |
| `hash_checker.py` | Gera hash (MD5/SHA-256) de arquivos e compara com uma lista de IOCs | planejado |
| `uptime_monitor.py` | Ping periódico em hosts e registro de quedas em CSV | planejado |
| `ioc_extractor.py` | Extrai IPs, domínios e hashes de um texto/relatório | planejado |

## Como usar

```bash
git clone https://github.com/innexosistemas-lang/security-scripts.git
cd security-scripts
python3 <script>.py --help
```

Cada script tem um `--help` e um exemplo de saída no próprio cabeçalho.

---
<sub>Uso apenas em sistemas próprios ou autorizados.</sub>
