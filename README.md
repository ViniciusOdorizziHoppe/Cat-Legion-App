# Cat Legion

Idle RPG de gatos feito em HTML5 Canvas + vanilla JavaScript.

## Features

- **3 Classes**: Guerreiro, Mago, Ninja — cada um com skill manual unica
- **Combate automatico**: 3 gatos vs hordas de inimigos
- **Skills manuais**: Ative a skill especial de cada gato (cooldown)
- **Drops**: Inimigos dropam armas, armaduras e acessorios
- **Inventario**: Gerencie equipamentos, equipe em cada gato
- **Loja**: Compre equipamentos aleatorios
- **Evolucao**: Gatos evoluem no nivel 20+ (stats boost)
- **Offline Gold**: Ganhe ouro mesmo com o jogo fechado
- **Save/Load**: Progresso salvo automaticamente no localStorage

## Como Jogar

1. Abra `index.html` em qualquer navegador
2. Clique em **Iniciar Wave** para comecar o combate
3. Clique nos botoes de **skill** (Garra Feroz / Bola de Fogo / Lamina Sombria) quando estiverem prontos
4. Derrote inimigos para ganhar gold, XP e drops
5. Use as abas **Time**, **Loja** e **Inventario** para gerenciar seus gatos
6. Seus gatos evoluem no nivel 20!

## Tech Stack

- HTML5 Canvas (renderizacao grafica)
- Vanilla JavaScript (zero frameworks)
- localStorage (save/load)
- Single-file (index.html = jogo completo)

## Deploy

### Web
Basta servir o arquivo `index.html` em qualquer servidor HTTP:
```bash
npx serve .        # servidor local
# ou
python -m http.server 8080
```

### Android APK (via Capacitor)
```bash
npm install
npx cap add android
npx cap sync
npx cap open android    # Abre no Android Studio para build
```

## Roadmap

- [x] 3 classes com skills manuais
- [x] Sistema de combate automatico
- [x] Drops e inventario
- [x] Loja
- [x] Offline gold
- [x] Evolucao lv20+
- [x] Save/Load localStorage
- [ ] Prestige system (reset com bonus)
- [ ] Mais gatos (desbloquear com gold)
- [ ] Modo PvP offline
- [ ] Mais tipos de inimigos e bosses

## Autor

Feito por Vinicius Odorizzi Hoppe
