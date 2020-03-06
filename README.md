# Party details - Gender

This extension adds a ```gender``` field to the parties.details object. For natural persons the field represents the gender of this and for enterprises it represents the gender of the person with more than 50% of the shares or is the manager

# Example

```json
        {
            "parties": [
                {
                    "name": "Siemens, SRL",
                    "id": "DO-RPE-12716",
                    "identifier": {
                        "scheme": "DO-RPE",
                        "id": "12716",
                        "legalName": "Siemens, SRL"
                    },
                    "roles": [
                        "supplier"
                    ],
                    "address": {
                        "streetAddress": "Avenida Pedro Henriquez Ureña No. 138, Torre Empresarial Reyna II, Piso 6 , 602, La Esperilla",
                        "locality": "SANTO DOMINGO DE GUZMAN",
                        "region": "DISTRITO NACIONAL"
                    },
                    "details": {
                        "gender": "male",
                        "scale": "notclassified"
                    }
            ]
        }
```