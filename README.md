# Fizz 🚀

Fizz is a cutting-edge web application built with Next.js that combines stunning 3D graphics with smooth animations and a modern content management system. It delivers an immersive and interactive user experience while maintaining high performance and type safety.

## 🛠️ Tech Stack

- **[Next.js](https://nextjs.org/)** - React framework for production
- **[Three.js](https://threejs.org/)** / **[React Three Fiber](https://docs.pmnd.rs/react-three-fiber)** - 3D graphics and visualization
- **[Prismic CMS](https://prismic.io/)** - Headless content management
- **[GSAP](https://greensock.com/gsap/)** - Professional-grade animations
- **[TypeScript](https://www.typescriptlang.org/)** - Static typing for JavaScript
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework

## 📋 Requirements

- Node.js 16.x or later
- npm or yarn package manager
- Git LFS for handling large files

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/GustavoGamarra95/Fizz.git
cd Fizz
```

2. Install Git LFS and pull the large files:
```bash
git lfs install
git lfs pull
```

3. Install dependencies:
```bash
npm install
# or
yarn install
```

4. Set up environment variables:
```bash
cp .env.example .env.local
```
Then edit `.env.local` with your configuration values.

## 💻 Development

Run the development server:
```bash
npm run dev
# or
yarn dev
```

Build for production:
```bash
npm run build
# or
yarn build
```

Start production server:
```bash
npm run start
# or
yarn start
```

Run type checking:
```bash
npm run type-check
# or
yarn type-check
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Run the tests and linting: `npm run test && npm run lint`
5. Commit your changes: `git commit -m 'Add some feature'`
6. Push to the branch: `git push origin feature/your-feature-name`
7. Submit a pull request

Please ensure your pull request adheres to the following guidelines:
- Follow the existing code style
- Update documentation as needed
- Add tests for new features
- Keep commits atomic and well-described

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

Copyright 2024 Fizz

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

