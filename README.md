# GTA 5 VR

Jogue o **GTA V (Modo História)** em realidade virtual pelo **SteamVR**, em primeira pessoa e com o corpo do personagem: os braços seguem os seus controles, as armas ficam em coldres no corpo e você mira com a própria arma.

> Só funciona no **GTA V Legacy** (DirectX 11), no **Modo História**. O GTA Online e o GTA V Enhanced não são suportados.

## O que o mod faz

- **Renderizador de VR próprio (SteamVR):** a visão segue a sua cabeça. A imagem é em 3D ou Mono, escolhida sozinha conforme o FPS.
- **Primeira pessoa com corpo:** você vê o corpo e os braços do personagem. Os braços seguem os controles e o corpo vira com você.
- **Armas nas mãos:** as armas ficam em coldres no corpo. Você pega com o grip, mira com a arma e atira com o gatilho. As pessoas reagem quando você aponta a arma para elas.
- **Recarga física (opcional):** tire o carregador, pegue outro no cinto e encaixe na arma. A escopeta de bomba e o rifle de precisão também são manuais.
- **Duas mãos:** a mão esquerda segura a frente da arma.
- **Granadas e armas brancas:** jogue a granada soltando o grip; golpeie balançando a arma.
- **Veículos:** gatilhos para acelerar e frear, analógico para virar.
- **Celular, troca de personagem e mapa:** celular no analógico direito, roda de personagens no Y, minimapa no pulso esquerdo (no painel, dentro do carro).
- **Cenas, menus e lojas** aparecem numa tela grande dentro do VR, e os menus funcionam com os controles.

## Requisitos

- GTA V **Legacy** para PC: Epic, Steam, Rockstar ou app do Xbox (PC Game Pass).
- **Script Hook V** e **ASI Loader** (`dinput8.dll`) da mesma versão do jogo: https://www.dev-c.com/gtav/scripthookv/
- **SteamVR** e um óculos de VR para PC. Testado com **Meta Quest** pelo Virtual Desktop. Os controles Touch (Quest / Rift) já vêm configurados; para outros controles, crie o mapeamento nas configurações de controle do SteamVR.

## Instalação

1. Coloque o Script Hook V e o `dinput8.dll` na pasta do GTA V.
2. Baixe o `gtavrmod.zip` e abra o **`gta5vrmod setup.exe`**. Ele acha a pasta do GTA V sozinho. Clique em **Install**.
3. Abra o **`GTA5 VR.exe`** na pasta do GTA V e escolha as opções.
4. Ligue o SteamVR e clique em **PLAY GTA 5 IN VR** (ou abra o GTA pela sua loja; no app do Xbox, abra pelo app).
5. Entre no **Modo História**. O VR começa quando ele termina de carregar.

Para desinstalar: botão **Uninstall** do `gta5vrmod setup.exe`. O GTA V e o Script Hook V continuam lá.

### Opções do launcher

| Opção | O que faz |
|---|---|
| First-person gameplay | Você vê pelos olhos do personagem. Desligado, o GTA aparece numa tela grande no VR. |
| Physical magazine reload | Recarga com as mãos (tirar, pegar e encaixar o carregador). |
| Support grip for heavier weapons | Fuzis e escopetas só atiram com a outra mão neles. |
| Show aiming laser | Um laser mostra para onde vão os tiros. |

## Controles (Touch)

### Mão esquerda

| Controle | Ação |
|---|---|
| Analógico | Andar (para onde você olha) |
| Clique do analógico | Correr |
| X | Pular |
| Y | Roda de personagens (aponte: esquerda Michael, cima Franklin, direita Trevor) |
| Grip | Segurar a frente da arma, pegar carregador no cinto, pegar granada no peito, bombear a escopeta |
| Gatilho | Frear / ré no veículo |

### Mão direita

| Controle | Ação |
|---|---|
| Gatilho | Atirar / acelerar no veículo |
| Grip | Pegar a arma no coldre (segure para manter, solte para guardar); granada: solte para jogar |
| A | Recarregar (tira o carregador); tecla **E** do GTA (com a mão sem arma, ou quando o jogo pede E); escolher no celular; freio de mão |
| B | Entrar / roubar / sair do veículo; voltar no celular |
| Analógico para os lados | Virar 30° |
| Analógico para cima | Celular (segure para cima para guardar) |
| Analógico para baixo | Próxima arma do mesmo coldre |
| Clique do analógico | Tecla **E** do GTA |

### Coldres

| Lugar | Armas |
|---|---|
| Quadril direito | Pistolas |
| Quadril esquerdo | Armas brancas |
| Peito | Granadas e outras armas de arremessar |
| Por cima do ombro direito | Submetralhadoras, fuzis, escopetas, metralhadoras |
| Por cima do ombro esquerdo | Rifles de precisão e armas pesadas |

### Gestos e teclado

| Ação | O que faz |
|---|---|
| Os dois analógicos clicados por 1 s (ou F11) | Liga / desliga o VR (tela plana) |
| Pose em T + os dois gatilhos por 2 s | Ajusta o corpo ao seu tamanho |
| F10 | Recentraliza a visão |
| Shift+F10 | Troca entre 3D e Mono |
| F8 | Liga / desliga os controles de movimento |
| Botão de menu do SteamVR | Pausa o GTA |

**No menu de pausa do GTA:** analógico = setas, A = Enter, B = voltar, X = Espaço, grips = abas, gatilhos = página. **Y abre o menu de VR**, onde você muda o que cada botão faz.

**Nas lojas:** analógico = setas, A = escolher / comprar, B = voltar / sair.

## Recarga física

1. Aperte **A**: o carregador cai.
2. Com a mão esquerda, aperte o grip no **cinto (frente esquerda)** ou por cima do ombro para pegar um carregador novo.
3. Encoste o carregador na arma: ele encaixa e a arma já atira.

Escopeta de bomba: depois de cada tiro, puxe e empurre a frente dela com a mão esquerda. Rifle de precisão: puxe o ferrolho (atrás da mira) com a mão esquerda.

## Dicas de desempenho

- No 3D cada olho recebe metade dos quadros. Por isso o modo automático usa **Mono** quando o jogo não roda quase na taxa do óculos (a 72 Hz, sempre Mono).
- Para 3D suave: óculos a **90 Hz** e o GTA a 90 FPS.
- Desligue o **VSync** do GTA e baixe os gráficos se precisar.

## Limitações

- No 3D os olhos se alternam: com FPS baixo a imagem trava ou duplica.
- Cutscenes aparecem numa tela plana.
- Só o Modo História do GTA V Legacy. Não use junto com outro mod de VR (como o `RealVR.asi`).

## Problemas

O topo do `GTA5 VR.exe` diz o que está faltando (Script Hook V, ASI Loader, SteamVR, arquivos do mod). Se algo der errado, mande o `GTAHandVR.log` e o `GTA5VRRenderer.log` da pasta do GTA V.

## Licença

MIT. Usa OpenVR (Valve, BSD-3-Clause) e MinHook (BSD-2-Clause). O Script Hook V não vem junto. GTA V é da Rockstar Games; este mod não tem ligação com a Rockstar.# GTA 5 VR

Play **GTA V (Story Mode)** in virtual reality with **SteamVR**, in first person with the character's full body: the arms follow your controllers, your weapons sit in holsters on your body, and you aim with the gun itself.

> Works only with **GTA V Legacy** (DirectX 11), in **Story Mode**. GTA Online and GTA V Enhanced are not supported.

## Features

- **Built-in VR renderer (SteamVR):** the view follows your head. The picture is 3D or Mono, chosen automatically from your FPS.
- **Full-body first person:** you see the character's body and arms. The arms follow your controllers and the body turns with you.
- **Weapons in your hands:** weapons sit in holsters on your body. Grab them with the grip, aim with the gun and fire with the trigger. People react when you point a gun at them.
- **Physical reloading (optional):** drop the magazine, grab a new one from your belt and push it into the gun. Pump shotguns and the sniper rifle are manual too.
- **Two-handed aiming:** your left hand holds the front of the gun.
- **Grenades and melee:** throw a grenade by letting go of the grip; hit by swinging the weapon.
- **Vehicles:** triggers to accelerate and brake, stick to steer.
- **Phone, character switching and map:** the phone is on the right stick, the character wheel on Y, and the minimap on your left wrist (on the dashboard in vehicles).
- **Cutscenes, menus and shops** show on a big screen inside VR, and the menus work with the controllers.

## Requirements

- GTA V **Legacy** for PC: Epic, Steam, Rockstar or the Xbox app (PC Game Pass).
- **Script Hook V** and the **ASI Loader** (`dinput8.dll`) for your game version: https://www.dev-c.com/gtav/scripthookv/
- **SteamVR** and a PC VR headset. Tested with **Meta Quest** through Virtual Desktop. Touch controllers (Quest / Rift) are set up out of the box; for other controllers, make a binding in SteamVR's controller settings.

## Installation

1. Put Script Hook V and `dinput8.dll` in your GTA V folder.
2. Download `gtavrmod.zip` and run **`gta5vrmod setup.exe`**. It finds your GTA V folder by itself. Click **Install**.
3. Open **`GTA5 VR.exe`** in your GTA V folder and pick your options.
4. Start SteamVR and click **PLAY GTA 5 IN VR** (or start GTA from your store; for the Xbox app, start it from the app).
5. Enter **Story Mode**. VR starts once it has finished loading.

To uninstall: the **Uninstall** button in `gta5vrmod setup.exe`. GTA V and Script Hook V stay.

### Launcher options

| Option | What it does |
|---|---|
| First-person gameplay | You see through the character's eyes. Off: GTA shows on a big screen in VR. |
| Physical magazine reload | Reload with your hands (drop, grab and insert the magazine). |
| Support grip for heavier weapons | Rifles and shotguns only fire with your other hand on them. |
| Show aiming laser | A laser shows where your shots go. |

## Controls (Touch)

### Left hand

| Control | Action |
|---|---|
| Stick | Walk (where you look) |
| Stick click | Run |
| X | Jump |
| Y | Character wheel (point: left Michael, up Franklin, right Trevor) |
| Grip | Hold the front of the gun, grab a magazine at your belt, grab a grenade at your chest, pump the shotgun |
| Trigger | Brake / reverse in vehicles |

### Right hand

| Control | Action |
|---|---|
| Trigger | Fire / accelerate in vehicles |
| Grip | Take a weapon from a holster (hold to keep it, let go to put it back); grenade: let go to throw |
| A | Reload (drops the magazine); GTA's **E** key (with no gun in your hand, or when the game asks for E); select on the phone; handbrake |
| B | Enter / steal / leave a vehicle; back on the phone |
| Stick left / right | Turn 30° |
| Stick up | Phone (hold up to put it away) |
| Stick down | Next weapon from the same holster |
| Stick click | GTA's **E** key |

### Holsters

| Where | Weapons |
|---|---|
| Right hip | Pistols |
| Left hip | Melee weapons |
| Chest | Grenades and other throwables |
| Over the right shoulder | SMGs, rifles, shotguns, machine guns |
| Over the left shoulder | Sniper rifles and heavy weapons |

### Gestures and keyboard

| Action | What it does |
|---|---|
| Both stick clicks held for 1 s (or F11) | VR on / off (flat screen) |
| T-pose + both triggers held for 2 s | Fits the body to your size |
| F10 | Recenter the view |
| Shift+F10 | Switch between 3D and Mono |
| F8 | Motion controls on / off |
| SteamVR menu button | Pauses GTA |

**In GTA's pause menu:** stick = arrow keys, A = Enter, B = back, X = Space, grips = tabs, triggers = page up / down. **Y opens the VR menu**, where you can change what each button does.

**In shops:** stick = arrow keys, A = choose / buy, B = back / leave.

## Physical reloading

1. Press **A**: the magazine drops out.
2. With your left hand, squeeze the grip at your **belt (front left)** or over your shoulder to take a new magazine.
3. Bring it to the gun: it slides in and the gun is ready to fire.

Pump shotguns: after each shot, pull the front back and push it forward with your left hand. Sniper rifle: work the bolt (behind the scope) with your left hand.

## Performance tips

- In 3D each eye gets half of the frames. That's why the automatic mode uses **Mono** when the game can't run close to your headset's refresh rate (at 72 Hz it's always Mono).
- For smooth 3D: set your headset to **90 Hz** and run GTA at 90 FPS.
- Turn off GTA's **VSync** and lower the graphics settings if needed.

## Limitations

- In 3D the eyes alternate: at low FPS the picture stutters or doubles.
- Cutscenes show on a flat screen.
- GTA V Legacy Story Mode only. Don't use it together with another VR mod (such as `RealVR.asi`).

## Troubleshooting

The top of `GTA5 VR.exe` tells you what's missing (Script Hook V, ASI Loader, SteamVR, mod files). If something goes wrong, send `GTAHandVR.log` and `GTA5VRRenderer.log` from your GTA V folder.

## License

MIT. Uses OpenVR (Valve, BSD-3-Clause) and MinHook (BSD-2-Clause). Script Hook V is not included. GTA V belongs to Rockstar Games; this mod is not affiliated with Rockstar.
