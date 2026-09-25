# 🏎️ OPV Race Engineer • EVO Edition (v1.2.0)

![OPV Race Engineer Banner](app_cover.png)

**OPV Race Engineer • EVO Edition** é o aplicativo oficial da **Liga OPV** para engenharia de pista, telemetria em tempo real e cálculo inteligente de estratégia, desenvolvido com **foco 100% exclusivo no Assetto Corsa EVO**.

A ferramenta foi projetada sob medida para a arquitetura de memória compartilhada do novo simulador da Kunos Simulazioni, garantindo leitura instantânea de dados oficiais de pista, cálculo de combustível preciso e calibração de pneus roda a roda com zero impacto no desempenho (FPS).

---

## 🟢 O Que Está Funcionando no Momento (Exclusivo Assetto Corsa EVO)

- ⚡ **Telemetria Direta (Shared Memory MMF):**
  - Conexão nativa e contínua com `Local\acevo_pmf_physics` e `Local\acevo_pmf_graphics` com buffer estendido de 4096 bytes.
  - Sem sobrecarga ou verificações em segundo plano para outros jogos.
- ⏱️ **Voltas e Tempos Oficiais de Pista:**
  - **Contagem Oficial de Voltas:** Leitura em tempo real das voltas completadas pelo piloto (`completedLaps`).
  - **Última Volta:** Leitura em milissegundos da última volta oficial completada (`iLastTime`).
  - **Melhor Volta:** Registro instantâneo do recorde pessoal na sessão (`iBestTime`).
- ⏳ **Relógio e Tempo de Sessão:**
  - Monitoramento contínuo do tempo restante de sessão (`sessionTimeLeft`) em treinos, classificações e corridas.
- ⛽ **Cálculo de Combustível Inteligente:**
  - Consumo médio real por volta (L/v) atualizado dinamicamente.
  - Combustível restante no tanque em tempo real.
  - Estimativa exata de litros necessários para cruzar a linha de chegada com margem de segurança configurável.
- 🎯 **Delta de Pressão Alvo (PSI) Roda a Roda:**
  - Monitoramento dinâmico de pressões e temperaturas nos 4 pneus (`FL`, `FR`, `RL`, `RR`).
  - Sugestão automática de ajuste a frio para alcançar o PSI ideal em temperatura de trabalho.
  - Alvos pré-calibrados por classe do AC EVO (Rua, Sport/Cup, Clássicos, Slick/GT e Chuva).
- 🛑 **Pit Wall & Estratégia de Box:**
  - Regras interativas de troca de pneus (Obrigatório / Opcional / Não) e reabastecimento (Obrigatório / Programado / Livre / Não).
  - Alerta sonoro configurável nos minutos finais da janela de pit stop.
- 🌍 **Interface Multilíngue (7 Idiomas):**
  - 🇧🇷 Português (Brasil) | 🇵🇹 Português (Portugal) | 🇺🇸 English | 🇪🇸 Español | 🇮🇹 Italiano | 🇩🇪 Deutsch | 🇫🇷 Français.
- 🪶 **Performance Ultraleve:**
  - Executável nativo em C# (.NET Framework do Windows), sem processos pesados, preservando os 100% de estabilidade térmica e fluidez da taxa de quadros (FPS) do simulador.

---

## 📥 Como Baixar e Usar (Download Oficial)

O aplicativo é distribuído em formato **Portable** (executável único, sem necessidade de instalação):

1. Acesse a seção de **[Releases Oficiais](https://github.com/ligaopv/OPVRaceEngineer/releases/latest)**.
2. Baixe o arquivo **`OPVRaceEngineer-v1.2.0-EVO.zip`** (ou `OPVRaceEngineer.exe`).
3. Extraia os arquivos na pasta de sua preferência no seu computador.
4. Execute o **`OPVRaceEngineer.exe`**.
5. Abra o **Assetto Corsa EVO**. O aplicativo detectará o jogo automaticamente e passará para o estado **"CONECTADO • ASSETTO CORSA EVO"**.

---

## 🎁 Modelo Comunitário & Liga OPV

O **OPV Race Engineer** é um projeto disponibilizado para a comunidade de pilotos virtuais:

- 📺 **YouTube:** [@ligaopv](https://www.youtube.com/@ligaopv)
- 📸 **Instagram:** [@ligaopv](https://www.instagram.com/ligaopv)
- 🏁 **The SimGrid:** [ligaopv](https://www.thesimgrid.com/communities/liga-opv-oficina-piloto-virtual)
- 🌐 **Portal Oficial:** [ligaopv.com.br](https://ligaopv.com.br/)
- ✉️ **Suporte / Dúvidas:** contato@ligaopv.com.br

---

## ⚖️ Termos de Uso e Licença

Distribuído sob licença de uso comunitário pela **Liga OPV**. Todos os direitos reservados sobre o software e código-fonte proprietário.
