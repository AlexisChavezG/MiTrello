# MiTrello
**Url para acceder al API de trello**  

***Acceder al API de trello para renombrar una tarjeta por ID***

*Request*  
*Tipo de funcion = ***PUT***  
 **id = Id de la tarjeta a modificar**  
 **name = nuevo nombre de la tarjeta**  
 **key = key personal obtenida de trello**  
  **key = key personal obtenida de trello**  
 ```
https://api.trello.com/1/cards/{id}?name={name}&key={key}&token={key}
```
{
    "id": "627c5d0ae0b46e1fcc607edf",
    "badges": {
        "attachmentsByType": {
            "trello": {
                "board": 0,
                "card": 0
            }
        },
        "location": false,
        "votes": 0,
        "viewingMemberVoted": false,
        "subscribed": false,
        "fogbugz": "",
        "checkItems": 0,
        "checkItemsChecked": 0,
        "checkItemsEarliestDue": null,
        "comments": 0,
        "attachments": 0,
        "description": false,
        "due": null,
        "dueComplete": false,
        "start": null
    },
    "checkItemStates": [],
    "closed": false,
    "dueComplete": false,
    "dateLastActivity": "2022-05-12T01:04:36.021Z",
    "desc": "",
    "descData": {
        "emoji": {}
    },
    "due": null,
    "dueReminder": null,
    "email": null,
    "idBoard": "627ae4be6f4f932ba35436c1",
    "idChecklists": [],
    "idList": "627ae4be6f4f932ba35436c2",
    "idMembers": [],
    "idMembersVoted": [],
    "idShort": 4,
    "idAttachmentCover": null,
    "labels": [],
    "idLabels": [],
    "manualCoverAttachment": false,
    "name": "nuevonombre2",
    "pos": 65536,
    "shortLink": "JpjfsMVp",
    "shortUrl": "https://trello.com/c/JpjfsMVp",
    "start": null,
    "subscribed": false,
    "url": "https://trello.com/c/JpjfsMVp/4-nuevonombre2",
    "cover": {
        "idAttachment": null,
        "color": null,
        "idUploadedBackground": null,
        "size": "normal",
        "brightness": "dark",
        "idPlugin": null
    },
    "isTemplate": false,
    "cardRole": null
}

***Acceder al APi de Trello para eliminar una card***

*Request*

*Tipo de funcion = ***DELETE***  
**id = id de la tarjeta a eliminar**  
**key = key personal obtenida de trello**  
**key = key personal obtenida de trello**  

```
https://api.trello.com/1/cards/{id}?key{key}=&token={key}
```
