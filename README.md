# 📊 Projeto de Pipeline de Dados em Tempo Real

**Objetivo**: Demonstração prática de um fluxo completo de dados em streaming usando AWS e Databricks.

## 🛠️ Tecnologias
- **AWS Kinesis** (Stream de dados)
- **AWS Firehose** (Exportação para S3)
- **AWS S3** (Armazenamento)
- **Databricks** (Notebooks Python)
- **Boto3** (Integração com AWS)

## 🔄 Fluxo Simplificado
1. `producer.ipynb` → Produz dados e envia para Kinesis
2. `consumer.ipynb` → Consome dados do stream em tempo real
3. **Firehose** → Entrega automática no S3
4. **S3** → Armazena os dados em formato JSON/Parquet

## 📸 Comprovantes Visuais
*(Todos na pasta `/evidencias`)*
1. `1-kinesis-stream.png` - Stream criado na AWS
2. `2-firehose.png` - Configuração do Firehose
3. `3-s3-bucket.png` - Bucket com os dados recebidos
4. `4-dados-raw.png` - Arquivo aberto mostrando os dados
5. `5-prod-output.png` - Saída do notebook de produção
6. `6-cons-output.png` - Saída do notebook de consumo

## 📂 Estrutura do Projeto
**/notebooks**  
- `producer.ipynb` (envia dados para o Kinesis)  
- `consumer.ipynb` (consome dados do stream)  

**/evidencias**  
- `1-kinesis-stream.png` (print do stream AWS)  
- `2-firehose.png` (config Firehose)  
- `3-s3-bucket.png` (bucket S3)  
- `4-dados-raw.png` (dados armazenados)  
- `5-prod-output.png` (output do producer)  
- `6-cons-output.png` (output do consumer)  


📬 Contato
- Kauan Silva
- https://biolink.website/socialKauanSilva
