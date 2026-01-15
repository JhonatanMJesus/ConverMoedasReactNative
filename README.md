# Conversor de Moedas 💱

Um aplicativo de conversão de moedas desenvolvido com React Native e Expo, oferecendo conversões em tempo real entre as principais moedas mundiais.

## 📱 Sobre o Projeto

Este é um conversor de moedas intuitivo e moderno que permite converter valores entre 8 diferentes moedas internacionais. O aplicativo utiliza a API ExchangeRate para obter taxas de câmbio atualizadas em tempo real.

### ✨ Funcionalidades

- 🔄 Conversão entre 8 moedas diferentes
- 💱 Taxas de câmbio em tempo real
- 🔀 Troca rápida entre moedas de origem e destino
- 📊 Visualização clara da taxa de conversão
- 🎨 Interface moderna e responsiva
- 🌙 Tema dark elegante

## 🌍 Moedas Suportadas

- 🇺🇸 Dólar Americano (USD)
- 🇧🇷 Real Brasileiro (BRL)
- 🇪🇺 Euro (EUR)
- 🇬🇧 Libra Esterlina (GBP)
- 🇯🇵 Iene Japonês (JPY)
- 🇨🇦 Dólar Canadense (CAD)
- 🇦🇺 Dólar Australiano (AUD)
- 🇨🇭 Franco Suíço (CHF)

## 🚀 Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [ExchangeRate API](https://www.exchangerate-api.com/)

## 📋 Pré-requisitos

Antes de começar, você precisa ter instalado em sua máquina:

- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/JhonatanMJesus/ConverMoedasReactNative.git
```

2. Acesse a pasta do projeto:
```bash
cd conversor-app
```

3. Instale as dependências:
```bash
npm install
# ou
yarn install
```

4. Inicie o projeto:
```bash
npm start
# ou
yarn start
```

## 📱 Executando o Aplicativo

### No Android:
```bash
npm run android
# ou
yarn android
```

### No iOS:
```bash
npm run ios
# ou
yarn ios
```

### No navegador (Web):
```bash
npm run web
# ou
yarn web
```

Você também pode escanear o QR Code gerado com o aplicativo Expo Go em seu dispositivo móvel.

## 📂 Estrutura do Projeto
```
conversor-app/
├── src/
│   ├── components/
│   │   ├── button/
│   │   ├── input/
│   │   └── resultCard/
│   ├── constants/
│   │   └── currencies.js
│   ├── services/
│   │   └── api.js
│   └── styles/
│       └── colors.js
├── utils/
│   └── convertCurrency.js
├── App.js
└── package.json
```

## 🎨 Paleta de Cores

- Primary: `#2563eb` (Azul)
- Secondary: `#16a34a` (Verde)
- Background: `#0f172a` (Azul escuro)
- Card Background: `#1e293b`
- Input Background: `#334155`

## 🤝 Como Contribuir

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT.

## 📞 Contato

- LinkedIn: [Jhonatan Marcelino](https://linkedin.com/in/jhonatanmjesus)

---

⭐ Se este projeto te ajudou, considere dar uma estrela!