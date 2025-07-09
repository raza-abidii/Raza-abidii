- Hi, I’m @Raza-abidi
- I’m interested in machine learning and blockchain technology
- I’m currently working on machine learning and deep learning
- I’m looking to collaborate on anything realted to web3, AI, ML
<!---
Raza-husain/Raza-husain is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
```mermaid
classDiagram
    class MainApp {
        +load_model()
        +predict(image)
        +display_results()
        +get_info(prediction, score)
    }
    class disease_info.py {
        plant_diseases_info
    }
    class User {
        +upload_image()
        +view_results()
    }
    class Model {
        <<ML Model>>
        +predict(image)
    }

    User --|> MainApp : interacts
    MainApp --> Model : uses
    MainApp --> disease_info.py : imports
    MainApp --> User : displays results
    Model <.. MainApp : prediction
    disease_info.py <.. MainApp : disease info lookup
```
