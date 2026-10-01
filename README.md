
![Build Status](https://github.com/sorolandry11/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)
# DevOps Capstone Template
   Microservice REST (Python Flask) de gestion des comptes clients d'un site e-commerce : créer, lire, mettre à jour, supprimer et lister des comptes.
   
```text
├── service         <- microservice package
│   ├── common/     <- common log and error handlers
│   ├── config.py   <- Flask configuration object
│   ├── models.py   <- code for the persistent model
│   └── routes.py   <- code for the REST API routes
├── setup.cfg       <- tools setup config
└── tests                       <- folder for all of the tests
    ├── factories.py            <- test factories
    ├── test_cli_commands.py    <- CLI tests
    ├── test_models.py          <- model unit tests
    └── test_routes.py          <- route unit tests
```

