# Atividade-murilo-node-red
[
    {
        "id": "ba4ccd33.b2a71",
        "type": "tab",
        "label": "Flow 1",
        "disabled": false,
        "info": ""
    },
    {
        "id": "d13301c1.c6392",
        "type": "tab",
        "label": "Flow 2",
        "disabled": false,
        "info": ""
    },
    {
        "id": "f2758d70.7428c",
        "type": "tab",
        "label": "Requisições HTTP",
        "disabled": false,
        "info": ""
    },
    {
        "id": "e5ddc63e.ca10a8",
        "type": "tab",
        "label": "Flow 3",
        "disabled": false,
        "info": ""
    },
    {
        "id": "7c9d1326.254d4c",
        "type": "ui_tab",
        "name": "FATEC",
        "icon": "dashboard",
        "disabled": false,
        "hidden": false
    },
    {
        "id": "a51d9bfc.55c198",
        "type": "ui_base",
        "theme": {
            "name": "theme-dark",
            "lightTheme": {
                "default": "#0094CE",
                "baseColor": "#0094CE",
                "baseFont": "-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Oxygen-Sans,Ubuntu,Cantarell,Helvetica Neue,sans-serif",
                "edited": true,
                "reset": false
            },
            "darkTheme": {
                "default": "#097479",
                "baseColor": "#097479",
                "baseFont": "-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Oxygen-Sans,Ubuntu,Cantarell,Helvetica Neue,sans-serif",
                "edited": true,
                "reset": false
            },
            "customTheme": {
                "name": "Untitled Theme 1",
                "default": "#4B7930",
                "baseColor": "#4B7930",
                "baseFont": "-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Oxygen-Sans,Ubuntu,Cantarell,Helvetica Neue,sans-serif"
            },
            "themeState": {
                "base-color": {
                    "default": "#097479",
                    "value": "#097479",
                    "edited": false
                },
                "page-titlebar-backgroundColor": {
                    "value": "#097479",
                    "edited": false
                },
                "page-backgroundColor": {
                    "value": "#111111",
                    "edited": false
                },
                "page-sidebar-backgroundColor": {
                    "value": "#333333",
                    "edited": false
                },
                "group-textColor": {
                    "value": "#0eb8c0",
                    "edited": false
                },
                "group-borderColor": {
                    "value": "#555555",
                    "edited": false
                },
                "group-backgroundColor": {
                    "value": "#333333",
                    "edited": false
                },
                "widget-textColor": {
                    "value": "#eeeeee",
                    "edited": false
                },
                "widget-backgroundColor": {
                    "value": "#097479",
                    "edited": false
                },
                "widget-borderColor": {
                    "value": "#333333",
                    "edited": false
                },
                "base-font": {
                    "value": "-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Oxygen-Sans,Ubuntu,Cantarell,Helvetica Neue,sans-serif"
                }
            },
            "angularTheme": {
                "primary": "indigo",
                "accents": "blue",
                "warn": "red",
                "background": "grey"
            }
        },
        "site": {
            "name": "Node-RED Dashboard",
            "hideToolbar": "false",
            "allowSwipe": "false",
            "lockMenu": "false",
            "allowTempTheme": "true",
            "dateFormat": "DD/MM/YYYY",
            "sizes": {
                "sx": 48,
                "sy": 48,
                "gx": 6,
                "gy": 6,
                "cx": 6,
                "cy": 6,
                "px": 0,
                "py": 0
            }
        }
    },
    {
        "id": "4506d23f.43c39c",
        "type": "ui_group",
        "name": "Ola mundo",
        "tab": "7c9d1326.254d4c",
        "order": 1,
        "disp": true,
        "width": "6",
        "collapse": false
    },
    {
        "id": "acac8a72.15c8d8",
        "type": "ui_group",
        "name": "Entrada texto",
        "tab": "7c9d1326.254d4c",
        "order": 2,
        "disp": true,
        "width": "6",
        "collapse": false
    },
    {
        "id": "1b8d62fe.e53e2d",
        "type": "ui_tab",
        "name": "HTTP",
        "icon": "wi-darksky-tornado",
        "disabled": false,
        "hidden": false
    },
    {
        "id": "fb6fcb76.f48838",
        "type": "ui_group",
        "name": "Clima",
        "tab": "1b8d62fe.e53e2d",
        "order": 1,
        "disp": true,
        "width": "6",
        "collapse": false
    },
    {
        "id": "5a5c75ed.9da48c",
        "type": "ui_tab",
        "name": "Servidor HTTP",
        "icon": "dashboard",
        "disabled": false,
        "hidden": false
    },
    {
        "id": "90b29fdd.31a9b",
        "type": "ui_group",
        "name": "Entrada",
        "tab": "5a5c75ed.9da48c",
        "order": 1,
        "disp": true,
        "width": "6",
        "collapse": false
    },
    {
        "id": "69150c1a.379c54",
        "type": "ui_group",
        "name": "Saida",
        "tab": "5a5c75ed.9da48c",
        "order": 2,
        "disp": true,
        "width": "6",
        "collapse": false
    },
    {
        "id": "7f08990d.0b9e98",
        "type": "inject",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "Ola Mundo",
        "payloadType": "str",
        "x": 120,
        "y": 80,
        "wires": [
            [
                "7fb5d503.78c11c"
            ]
        ]
    },
    {
        "id": "7fb5d503.78c11c",
        "type": "debug",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "false",
        "statusVal": "",
        "statusType": "auto",
        "x": 330,
        "y": 80,
        "wires": []
    },
    {
        "id": "e2332927.ae03b8",
        "type": "inject",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 100,
        "y": 180,
        "wires": [
            [
                "5c4c51e8.039b6"
            ]
        ]
    },
    {
        "id": "9a4f995d.cad0b8",
        "type": "debug",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "active": false,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "true",
        "targetType": "full",
        "statusVal": "",
        "statusType": "auto",
        "x": 450,
        "y": 140,
        "wires": []
    },
    {
        "id": "5c4c51e8.039b6",
        "type": "change",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "rules": [
            {
                "t": "set",
                "p": "payload",
                "pt": "msg",
                "to": "Embarcados",
                "tot": "str"
            },
            {
                "t": "set",
                "p": "Curso",
                "pt": "flow",
                "to": "Mecatrônica",
                "tot": "str"
            }
        ],
        "action": "",
        "property": "",
        "from": "",
        "to": "",
        "reg": false,
        "x": 280,
        "y": 160,
        "wires": [
            [
                "9a4f995d.cad0b8"
            ]
        ]
    },
    {
        "id": "f6ee2a03.0aee48",
        "type": "inject",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 100,
        "y": 280,
        "wires": [
            [
                "3882188e.aaee38"
            ]
        ]
    },
    {
        "id": "3882188e.aaee38",
        "type": "change",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "rules": [
            {
                "t": "set",
                "p": "payload",
                "pt": "msg",
                "to": "Curso",
                "tot": "flow"
            }
        ],
        "action": "",
        "property": "",
        "from": "",
        "to": "",
        "reg": false,
        "x": 280,
        "y": 280,
        "wires": [
            [
                "7f9f8b9f.815dc4"
            ]
        ]
    },
    {
        "id": "7f9f8b9f.815dc4",
        "type": "debug",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "payload",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 470,
        "y": 280,
        "wires": []
    },
    {
        "id": "b4b19b77.b41548",
        "type": "inject",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "props": [
            {
                "p": "payload"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "1",
        "payloadType": "num",
        "x": 90,
        "y": 360,
        "wires": [
            [
                "afe485a.b29ed78"
            ]
        ]
    },
    {
        "id": "afe485a.b29ed78",
        "type": "switch",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "property": "payload",
        "propertyType": "msg",
        "rules": [
            {
                "t": "eq",
                "v": "1",
                "vt": "num"
            },
            {
                "t": "eq",
                "v": "2",
                "vt": "num"
            },
            {
                "t": "eq",
                "v": "3",
                "vt": "num"
            }
        ],
        "checkall": "true",
        "repair": false,
        "outputs": 3,
        "x": 250,
        "y": 380,
        "wires": [
            [
                "a2c530c1.3bde2"
            ],
            [
                "dc698dfa.14686"
            ],
            [
                "af2881e2.7ca4b"
            ]
        ]
    },
    {
        "id": "a2c530c1.3bde2",
        "type": "change",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "rules": [
            {
                "t": "set",
                "p": "Curso",
                "pt": "flow",
                "to": "mecatronica",
                "tot": "str"
            }
        ],
        "action": "",
        "property": "",
        "from": "",
        "to": "",
        "reg": false,
        "x": 420,
        "y": 340,
        "wires": [
            []
        ]
    },
    {
        "id": "dc698dfa.14686",
        "type": "change",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "rules": [
            {
                "t": "set",
                "p": "Curso",
                "pt": "flow",
                "to": "goku",
                "tot": "str"
            }
        ],
        "action": "",
        "property": "",
        "from": "",
        "to": "",
        "reg": false,
        "x": 420,
        "y": 380,
        "wires": [
            []
        ]
    },
    {
        "id": "af2881e2.7ca4b",
        "type": "change",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "rules": [
            {
                "t": "set",
                "p": "Curso",
                "pt": "flow",
                "to": "vegeta",
                "tot": "str"
            }
        ],
        "action": "",
        "property": "",
        "from": "",
        "to": "",
        "reg": false,
        "x": 420,
        "y": 420,
        "wires": [
            []
        ]
    },
    {
        "id": "ae6e977f.940168",
        "type": "inject",
        "z": "ba4ccd33.b2a71",
        "name": "",
        "props": [
            {
                "p": "payload"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "2",
        "payloadType": "num",
        "x": 90,
        "y": 400,
        "wires": [
            [
                "afe485a.b29ed78"
            ]
        ]
    },
    {
        "id": "7b2d961b.eadb88",
        "type": "ui_button",
        "z": "d13301c1.c6392",
        "name": "",
        "group": "4506d23f.43c39c",
        "order": 0,
        "width": 0,
        "height": 0,
        "passthru": false,
        "label": "Olá",
        "tooltip": "acione para ter uma surpresa",
        "color": "",
        "bgcolor": "",
        "icon": "fa-handshake-o",
        "payload": "Ola mundo dashboard",
        "payloadType": "str",
        "topic": "payload",
        "topicType": "msg",
        "x": 70,
        "y": 80,
        "wires": [
            [
                "cfcc21fa.0adfc"
            ]
        ]
    },
    {
        "id": "cfcc21fa.0adfc",
        "type": "ui_text",
        "z": "d13301c1.c6392",
        "group": "4506d23f.43c39c",
        "order": 1,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "mensagem recebida",
        "format": "{{msg.payload}}",
        "layout": "col-center",
        "x": 320,
        "y": 80,
        "wires": []
    },
    {
        "id": "d4c5865c.8adc78",
        "type": "ui_text_input",
        "z": "d13301c1.c6392",
        "name": "",
        "label": "informe seu nome",
        "tooltip": "Digite aqui o nome de asuario",
        "group": "acac8a72.15c8d8",
        "order": 0,
        "width": 0,
        "height": 0,
        "passthru": true,
        "mode": "number",
        "delay": "0",
        "topic": "topic",
        "topicType": "msg",
        "x": 110,
        "y": 180,
        "wires": [
            [
                "5764f77f.a2bc08"
            ]
        ]
    },
    {
        "id": "5764f77f.a2bc08",
        "type": "ui_text",
        "z": "d13301c1.c6392",
        "group": "acac8a72.15c8d8",
        "order": 1,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "Mensagem recebida",
        "format": "{{msg.payload}}",
        "layout": "col-center",
        "x": 400,
        "y": 180,
        "wires": []
    },
    {
        "id": "76befd59.71e0b4",
        "type": "inject",
        "z": "f2758d70.7428c",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 100,
        "y": 60,
        "wires": [
            [
                "b9c606a2.6311a8"
            ]
        ]
    },
    {
        "id": "339b3251.152afe",
        "type": "http request",
        "z": "f2758d70.7428c",
        "name": "",
        "method": "use",
        "ret": "obj",
        "paytoqs": "ignore",
        "url": "",
        "tls": "",
        "persist": false,
        "proxy": "",
        "authType": "",
        "x": 430,
        "y": 60,
        "wires": [
            [
                "39a95eda.5fe592",
                "9d48948d.259df8",
                "f6530294.681cb"
            ]
        ]
    },
    {
        "id": "b9c606a2.6311a8",
        "type": "change",
        "z": "f2758d70.7428c",
        "name": "",
        "rules": [
            {
                "t": "set",
                "p": "method",
                "pt": "msg",
                "to": "get",
                "tot": "str"
            },
            {
                "t": "set",
                "p": "url",
                "pt": "msg",
                "to": "http://api.openweathermap.org/data/2.5/weather?q=Santo Andre,BR-SP&appid=eb265000fca9f9f968217446ce5c8a59&units=metric",
                "tot": "str"
            }
        ],
        "action": "",
        "property": "",
        "from": "",
        "to": "",
        "reg": false,
        "x": 260,
        "y": 140,
        "wires": [
            [
                "339b3251.152afe"
            ]
        ]
    },
    {
        "id": "39a95eda.5fe592",
        "type": "debug",
        "z": "f2758d70.7428c",
        "name": "",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "true",
        "targetType": "full",
        "statusVal": "",
        "statusType": "auto",
        "x": 570,
        "y": 80,
        "wires": []
    },
    {
        "id": "eb673bd6.de4618",
        "type": "ui_button",
        "z": "f2758d70.7428c",
        "name": "",
        "group": "fb6fcb76.f48838",
        "order": 0,
        "width": 0,
        "height": 0,
        "passthru": false,
        "label": "Atualizar temperatura",
        "tooltip": "Clique para atualizar os dados de clima",
        "color": "",
        "bgcolor": "",
        "icon": "",
        "payload": "",
        "payloadType": "str",
        "topic": "topic",
        "topicType": "msg",
        "x": 120,
        "y": 260,
        "wires": [
            [
                "b9c606a2.6311a8"
            ]
        ]
    },
    {
        "id": "9d48948d.259df8",
        "type": "ui_text",
        "z": "f2758d70.7428c",
        "group": "fb6fcb76.f48838",
        "order": 1,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "Temperatura Atual (Graus C):",
        "format": "{{msg.payload.main.temp}}",
        "layout": "col-center",
        "x": 640,
        "y": 120,
        "wires": []
    },
    {
        "id": "f6530294.681cb",
        "type": "ui_text",
        "z": "f2758d70.7428c",
        "group": "fb6fcb76.f48838",
        "order": 2,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "Umidade Relativa (%):",
        "format": "{{msg.payload.main.humidity}}",
        "layout": "col-center",
        "x": 620,
        "y": 160,
        "wires": []
    },
    {
        "id": "68cd99df.a43378",
        "type": "http in",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "url": "/ola",
        "method": "get",
        "upload": false,
        "swaggerDoc": "",
        "x": 80,
        "y": 100,
        "wires": [
            [
                "8f009bb7.f137f8"
            ]
        ]
    },
    {
        "id": "8f009bb7.f137f8",
        "type": "template",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "field": "payload",
        "fieldType": "msg",
        "format": "json",
        "syntax": "mustache",
        "template": "{\n    \"mensagem\":\"ola\"\n}",
        "output": "str",
        "x": 220,
        "y": 100,
        "wires": [
            [
                "51484b2a.b07a84"
            ]
        ]
    },
    {
        "id": "51484b2a.b07a84",
        "type": "http response",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "statusCode": "200",
        "headers": {},
        "x": 360,
        "y": 100,
        "wires": []
    },
    {
        "id": "65c87c16.0ffdc4",
        "type": "http in",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "url": "/ola-nome",
        "method": "get",
        "upload": false,
        "swaggerDoc": "",
        "x": 80,
        "y": 180,
        "wires": [
            [
                "f81abc15.9d463"
            ]
        ]
    },
    {
        "id": "f3d572e8.8d8dc",
        "type": "http response",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "statusCode": "200",
        "headers": {},
        "x": 420,
        "y": 180,
        "wires": []
    },
    {
        "id": "f81abc15.9d463",
        "type": "function",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "func": "msg.payload = {\n    \"nome-enviado\":msg.req.query.nome,\n    \"tamanho\":msg.req.query.nome.length\n};\nreturn msg;",
        "outputs": 1,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 260,
        "y": 180,
        "wires": [
            [
                "f3d572e8.8d8dc"
            ]
        ]
    },
    {
        "id": "bc38f31.1da751",
        "type": "http in",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "url": "/calculadora",
        "method": "get",
        "upload": false,
        "swaggerDoc": "",
        "x": 80,
        "y": 260,
        "wires": [
            [
                "95e48796.4f7f58"
            ]
        ]
    },
    {
        "id": "95e48796.4f7f58",
        "type": "function",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "func": "var num1 = parseInt(msg.req.query.n1, 10); //converte string para Int\nvar num2 = parseInt(msg.req.query.n2, 10); //converte string para Int\nvar resultado = num1+num2;\nmsg.payload = {\n    \"num1\":num1,\n    \"num2\":num2,\n    \"operacao\":\"+\",\n    \"resultado\":resultado\n};\nmsg.statusCode = 200;\nreturn msg;",
        "outputs": 1,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 260,
        "y": 260,
        "wires": [
            [
                "59a64731.d4c758"
            ]
        ]
    },
    {
        "id": "59a64731.d4c758",
        "type": "http response",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "statusCode": "",
        "headers": {},
        "x": 410,
        "y": 260,
        "wires": []
    },
    {
        "id": "2ac6d24c.94ab3e",
        "type": "http in",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "url": "/calculadora-basica",
        "method": "get",
        "upload": false,
        "swaggerDoc": "",
        "x": 110,
        "y": 340,
        "wires": [
            [
                "c7aa8464.38e9f8"
            ]
        ]
    },
    {
        "id": "c7aa8464.38e9f8",
        "type": "function",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "func": "var num1 = parseInt(msg.req.query.n1, 10); //converte string para Int\nvar num2 = parseInt(msg.req.query.n2, 10); //converte string para Int\nvar operacao = msg.req.query.operacao;\nvar resultado;\nif (operacao == \"plus\")\n    resultado = num1+num2;\nelse if(operacao == \"-\")\n    resultado = num1-num2;\nelse if(operacao == \"*\")\n    resultado = num1*num2;\nelse if(operacao == \"/\")\n    resultado = num1/num2;\nmsg.payload = {\n    \"num1\":num1,\n    \"num2\":num2,\n    \"operacao\":operacao,\n    \"resultado\":resultado\n};\nmsg.statusCode = 200;\nreturn msg;",
        "outputs": 1,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 280,
        "y": 400,
        "wires": [
            [
                "9f2cb614.787658"
            ]
        ]
    },
    {
        "id": "9f2cb614.787658",
        "type": "http response",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "statusCode": "",
        "headers": {},
        "x": 390,
        "y": 340,
        "wires": []
    },
    {
        "id": "31bb1573.9aa72a",
        "type": "ui_switch",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "label": "switch",
        "tooltip": "",
        "group": "90b29fdd.31a9b",
        "order": 0,
        "width": 0,
        "height": 0,
        "passthru": true,
        "decouple": "false",
        "topic": "topic",
        "topicType": "msg",
        "style": "",
        "onvalue": "true",
        "onvalueType": "bool",
        "onicon": "",
        "oncolor": "",
        "offvalue": "false",
        "offvalueType": "bool",
        "officon": "",
        "offcolor": "",
        "animate": false,
        "x": 70,
        "y": 460,
        "wires": [
            [
                "8f5ec2eb.1afe2"
            ]
        ]
    },
    {
        "id": "8228253e.3e2d58",
        "type": "ui_slider",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "label": "slider",
        "tooltip": "",
        "group": "90b29fdd.31a9b",
        "order": 2,
        "width": 0,
        "height": 0,
        "passthru": true,
        "outs": "end",
        "topic": "topic",
        "topicType": "msg",
        "min": 0,
        "max": "255",
        "step": 1,
        "x": 70,
        "y": 540,
        "wires": [
            [
                "5540b508.53ef4c"
            ]
        ]
    },
    {
        "id": "beaac870.b93808",
        "type": "ui_gauge",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "group": "69150c1a.379c54",
        "order": 0,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "gauge",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": 10,
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "x": 410,
        "y": 600,
        "wires": []
    },
    {
        "id": "5540b508.53ef4c",
        "type": "change",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "rules": [
            {
                "t": "set",
                "p": "slider",
                "pt": "flow",
                "to": "payload",
                "tot": "msg"
            }
        ],
        "action": "",
        "property": "",
        "from": "",
        "to": "",
        "reg": false,
        "x": 240,
        "y": 540,
        "wires": [
            []
        ]
    },
    {
        "id": "8f5ec2eb.1afe2",
        "type": "change",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "rules": [
            {
                "t": "set",
                "p": "switch",
                "pt": "flow",
                "to": "payload",
                "tot": "msg"
            }
        ],
        "action": "",
        "property": "",
        "from": "",
        "to": "",
        "reg": false,
        "x": 240,
        "y": 460,
        "wires": [
            []
        ]
    },
    {
        "id": "cb8e3377.dfd29",
        "type": "change",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "rules": [
            {
                "t": "set",
                "p": "slider",
                "pt": "flow",
                "to": "0",
                "tot": "num"
            },
            {
                "t": "set",
                "p": "switch",
                "pt": "flow",
                "to": "false",
                "tot": "bool"
            },
            {
                "t": "set",
                "p": "gauge",
                "pt": "flow",
                "to": "5",
                "tot": "num"
            }
        ],
        "action": "",
        "property": "",
        "from": "",
        "to": "",
        "reg": false,
        "x": 300,
        "y": 700,
        "wires": [
            []
        ]
    },
    {
        "id": "16d2776c.f68c29",
        "type": "trigger",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "op1": "gauge",
        "op2": "0",
        "op1type": "flow",
        "op2type": "str",
        "duration": "-300",
        "extend": false,
        "overrideDelay": false,
        "units": "ms",
        "reset": "",
        "bytopic": "all",
        "topic": "topic",
        "outputs": 1,
        "x": 240,
        "y": 600,
        "wires": [
            [
                "beaac870.b93808"
            ]
        ]
    },
    {
        "id": "16c07bd4.ddea64",
        "type": "inject",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": true,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 90,
        "y": 700,
        "wires": [
            [
                "cb8e3377.dfd29",
                "16d2776c.f68c29"
            ]
        ]
    },
    {
        "id": "445a9657.c447a8",
        "type": "function",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "func": "msg.payload = {\n    \"slider\":flow.get(\"slider\"),\n    \"gauge\":flow.get(\"gauge\"),\n    \"switch\":flow.get(\"switch\"),\n};\nmsg.statusCode = 200;\nreturn msg;",
        "outputs": 1,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 260,
        "y": 780,
        "wires": [
            [
                "d04da613.c48e58"
            ]
        ]
    },
    {
        "id": "9ddd32a2.595ea",
        "type": "http in",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "url": "/get-status",
        "method": "get",
        "upload": false,
        "swaggerDoc": "",
        "x": 100,
        "y": 780,
        "wires": [
            [
                "445a9657.c447a8"
            ]
        ]
    },
    {
        "id": "d04da613.c48e58",
        "type": "http response",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "statusCode": "",
        "headers": {},
        "x": 390,
        "y": 780,
        "wires": []
    },
    {
        "id": "f7d8d9dc.0d0a98",
        "type": "http in",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "url": "/atualiza-gauge",
        "method": "post",
        "upload": false,
        "swaggerDoc": "",
        "x": 110,
        "y": 860,
        "wires": [
            []
        ]
    },
    {
        "id": "b1787034.384fe",
        "type": "http response",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "statusCode": "",
        "headers": {},
        "x": 430,
        "y": 860,
        "wires": []
    },
    {
        "id": "d69edc66.a795c",
        "type": "function",
        "z": "e5ddc63e.ca10a8",
        "name": "",
        "func": "//pega o valor q veio no post\nvar novo_gauge = msg.payload.value;\n//seta o valor do post dentro do gauge\nflow.set(\"gauge\", novo_valor);\n//prepara o retorno para a requisição \nmsg.payload = {\n    \"gauge\":flow.get(\"gauge\")\n};\nmsg.statusCode = 200;\nreturn msg;",
        "outputs": 1,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 300,
        "y": 860,
        "wires": [
            []
        ]
    }
]
