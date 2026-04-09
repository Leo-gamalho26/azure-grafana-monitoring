# Monitoramento com Grafana e Docker no Azure (PaaS)

Este projeto demonstra a implementação de uma solução de observabilidade utilizando o Grafana hospedado no Azure App Service.

## 🚀 Arquitetura do Projeto
- **Provedor Cloud:** Microsoft Azure (Assinatura Student)
- **Serviço de Hospedagem:** Azure App Service (Plataforma como Serviço - PaaS)
- **Containerização:** Docker (Imagem oficial `grafana/grafana-oss`)
- **Gestão de Configuração:** Variáveis de ambiente no Azure

## 🛠️ Desafios Técnicos Superados
Durante o deploy, foram aplicadas as seguintes configurações de infraestrutura:
1. **Mapeamento de Portas:** Configuração da variável `WEBSITES_PORT` para direcionar o tráfego da porta 80 do Azure para a porta 3000 do container.
2. **Otimização de Inicialização:** Ajuste da variável `WEBSITES_CONTAINER_START_TIME_LIMIT` para lidar com o tempo de migração do banco de dados interno em instâncias de baixo custo (F1 Free Tier).

## 📸 Como acessar
O serviço está sendo provisionado em: `https://[SUA-URL-AQUI].azurewebsites.net`# azure-grafana-monitoring
respositorio do Azure do meu grafana que ainda esta rodando
