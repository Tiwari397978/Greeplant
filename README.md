## About 🔮

- Creates a TensorFlow Model for identifying plant diseases
- Creates optimized TensorFlow JS Models
- Uses TensorFlow JS to perform inferences on-device
- Creates a fully functional web app using React
- Exposes a hosted API built with TensorFlow Serving for inferences from the TensorFlow Model

## UI Design 🎨

Click to View Plant AI web app Design from below

[![Plant AI Design](https://img.shields.io/badge/PlantAI-FIGMA-black.svg?style=for-the-badge&logo=figma)](https://www.figma.com/file/RbfBDLPgNNTtLp5xmvJEEH/Plant-AI-Hackathon-Website)

This notebook contains the code to train a model on the [PlantVillage dataset](http://arxiv.org/abs/1511.08060)
to identify diseases from plant images. Here we provide a subset of our 
experiments on working with this data. Finally we export our model as a 
TensorFlow `SavedModel`.

## Run Locally

To get up and running with this web-app, run the following commands, make sure 
you have [Node.js](http://nodejs.org/) installed. This runs the app in 
development mode:

```sh
git clone https://github.com/Tiwari397978/Greeplant # or clone your own fork
cd Greeplant
npm install
npm start
```

<!-- markdown-link-check-disable-next-line -->
Your app should now be running on [localhost:3000](http://localhost:3000) :rocket:.

## Lint ✅
This project uses [***GitHub Super Linter***](https://github.com/github/super-linter) which is Combination of multiple linters to install as a GitHub Action.

Following Linters are used internally by super linter (enabled for this project):
- JavaScript: [eslint](https://eslint.org/)
- CSS: [stylelint](https://stylelint.io/)
- HTML: [HTMLHint](https://github.com/htmlhint/HTMLHint)
- JSON: [jsonlint](https://github.com/zaach/jsonlint)
- YAML: [YamlLint](https://github.com/adrienverge/yamllint)

## Want to Contribute 🙋‍♂️?

Awesome! If you want to contribute to this project, you're always welcome! See [Contributing Guidelines](CONTRIBUTING.md). You can also take a look at [Gree-Plant Project Status Tracker] for getting more information about current or upcoming tasks.

## Want to discuss? 💬

Have any questions, doubts or want to present your opinions, views? You're always welcome. You can [start discussions](https://github.com/Tiwari397978/Gree-Plant/discussions).

## Citations

```bibtex
@misc{hughes2016open,
      title={An open access repository of images on plant health to enable the development of mobile disease diagnostics}, 
      author={David. P. Hughes and Marcel Salathe},
      year={2016},
      eprint={1511.08060},
      archivePrefix={arXiv},
      primaryClass={cs.CY}
}
```

## License

```

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
