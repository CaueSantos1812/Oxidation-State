# Oxidation-State

Este repositório contém a implementação de métodos computacionais para determinar estados de oxidação em compostos utilizando espectros XANES (X-ray Absorption Near Edge Structure) e a implementação do método de Rising Sun nesses mesmos espectros para a determinação de máximos e mínimos. O projeto utiliza técnicas de análise espectral e programação em Python para explorar relações lineares entre parâmetros espectrais e estados de oxidação, além do método para os máximos e mínimos, conforme descrito em trabalhos de referência da literatura científica em espectroscopia de absorção de raios-X.
---
# Objetivo  

Desenvolver um pipeline computacional capaz de:  
1. Calcular o deslocamento de borda (\(\Delta E\)) em espectros XANES.  
2. Aplicar métodos baseados na integral da borda de absorção (Capehart et al.).  
3. Validar as relações lineares estabelecidas (Wong et al.).  
4. Propor melhorias e discutir limitações do método aplicado.

---

## Métodos  

O projeto utiliza:  
- **Python**: Scripts para processamento e análise dos espectros.  
- **Jupyter Notebooks**: Interatividade e visualização dos resultados.  
- **HPC da Ilum**: Execução de cálculos em larga escala.  
- **Base de Dados Cruzeiro do Sul Utils**: Repositório de espectros XDI utilizado para análise.  
