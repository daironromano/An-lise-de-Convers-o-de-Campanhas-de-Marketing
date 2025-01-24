# Analise-de-Conversao-de-Campanhas-de-Marketing
Uma simulação de uma "Análise de Conversão de Campanhas de Marketing"

# **Análise de Conversão de Campanhas de Marketing**

Uma empresa realizou **campanhas de marketing** em diversos canais para atrair novos clientes. Cada canal gerou um número específico de **visitas** e obteve um número de **conversões** (vendas ou cadastros).

## **Objetivo**

1. Calcular e exibir a **taxa de conversão (%)** de cada canal.  
2. Identificar e exibir:
   - O canal com a **maior taxa de conversão**.  
   - O canal com a **menor taxa de conversão**.  

---

## **Dados**

Os dados fornecidos são:
- Um **dicionário** contendo, para cada canal, a quantidade de **visitas** e **conversões**.  

Dados:

```python

dados_marketing = {
    "E-mail": {"visitas": 5000, "conversoes": 400},
    "Redes Sociais": {"visitas": 8000, "conversoes": 480},
    "Anúncios Pagos": {"visitas": 12000, "conversoes": 720},
    "SEO": {"visitas": 15000, "conversoes": 600},
    "YouTube Ads": {"visitas": 9000, "conversoes": 450},
    "Google Ads": {"visitas": 11000, "conversoes": 700},
    "TikTok Ads": {"visitas": 7000, "conversoes": 350},
    "Influenciadores": {"visitas": 10000, "conversoes": 300},
    "Blog": {"visitas": 14000, "conversoes": 560},
    "LinkedIn Ads": {"visitas": 6000, "conversoes": 300},
    "WhatsApp Marketing": {"visitas": 4000, "conversoes": 280},
    "SMS Marketing": {"visitas": 3000, "conversoes": 180},
    "Eventos": {"visitas": 2000, "conversoes": 250}
}
```

---

## **Regras**

1. Calcule a **taxa de conversão** para cada canal usando a seguinte fórmula:  

![image.png](attachment:image.png)

   - As taxas devem ser exibidas com **duas casas decimais**.  

2. Identifique o canal com a **maior taxa de conversão** e o canal com a **menor taxa de conversão**.  

---

## **Formato de Saída**

O programa deve exibir as informações no seguinte formato:

```
Taxa de conversão por canal:
- E-mail: 8.00%
- Redes Sociais: 6.00%
- Anúncios Pagos: 6.00%
- SEO: 4.00%
- YouTube Ads: 5.00%
- Google Ads: 6.36%
- TikTok Ads: 5.00%
- Influenciadores: 3.00%
- Blog: 4.00%
- LinkedIn Ads: 5.00%
- WhatsApp Marketing: 7.00%
- SMS Marketing: 6.00%
- Eventos: 12.50%

Canal com maior taxa de conversão: Eventos (12.50%)
Canal com menor taxa de conversão: Influenciadores (3.00%)
```

---

# **Parte 2: Classificação dos Canais de Marketing**

Com base nas **taxas de conversão** calculadas na primeira parte, o programa deve agora **classificar** os canais de marketing em categorias.

## **Objetivo**

1. Classificar cada canal em uma das seguintes categorias, com base em sua **taxa de conversão**:  
   - **Excelente**: Taxa de conversão superior a **10%**.  (conversão > 10%)
   - **Bom**: Taxa de conversão entre **5% e 10%** (conversão >= 5% e conversão >= 10%).  
   - **Precisa Melhorar**: Taxa de conversão inferior a **5%**.  (conversão < 5%)

2. Exibir a classificação de cada canal no seguinte formato:

```
Classificação dos Canais:
- E-mail: Bom
- Redes Sociais: Bom
- Anúncios Pagos: Bom
- SEO: Precisa Melhorar
- YouTube Ads: Bom
- Google Ads: Bom
- TikTok Ads: Bom
- Influenciadores: Precisa Melhorar
- Blog: Precisa Melhorar
- LinkedIn Ads: Bom
- WhatsApp Marketing: Bom
- SMS Marketing: Bom
- Eventos: Excelente
```

---

## **Regras**

1. As classificações devem seguir as seguintes regras:  

   - **Excelente**: Taxa > 10%  
   - **Bom**: 5% ≤ Taxa ≤ 10%  
   - **Precisa Melhorar**: Taxa < 5%  

2. Garanta que o programa utilize os valores calculados na **Parte 1**.  

# **Parte 3: Conte quantos canais pertencem a cada categoria**

## **Regras:**

1. exiba o resultado final no seguinte formato:

```
Resumo Final:
- Excelente: 1 
- Bom: 9 
- Precisa Melhorar: 3 
```