````json
[
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Adresse",
    "expression": "value.toTitlecase()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Adresse using expression value.toTitlecase()"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Ville",
    "expression": "value.toTitlecase()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Ville using expression value.toTitlecase()"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Nom",
    "expression": "value.toTitlecase()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Nom using expression value.toTitlecase()"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Identifiant",
    "expression": "value.trim()",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Identifiant using expression value.trim()"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix Gazole",
    "expression": "grel:value +\"00\"[0,5-value.length()]",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Prix Gazole using expression grel:value +\"00\"[0,5-value.length()]"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP95",
    "expression": "grel:value +\"000\"[0,5-value.length()]",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Prix SP95 using expression grel:value +\"000\"[0,5-value.length()]"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP98",
    "expression": "grel:value +\"000\"[0,5-value.length()]",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Prix SP98 using expression grel:value +\"000\"[0,5-value.length()]"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix GPLc",
    "expression": "grel:value +\"000\"[0,5-value.length()]",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Prix GPLc using expression grel:value +\"000\"[0,5-value.length()]"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix E10",
    "expression": "grel:value +\"000\"[0,5-value.length()]",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Prix E10 using expression grel:value +\"000\"[0,5-value.length()]"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix E85",
    "expression": "grel:value +\"000\"[0,5-value.length()]",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Prix E85 using expression grel:value +\"000\"[0,5-value.length()]"
  },
  {
    "op": "core/text-transform",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix E85",
    "expression": "grel:value +\"000\"[0,5-value.length()]",
    "onError": "keep-original",
    "repeat": false,
    "repeatCount": 10,
    "description": "Text transform on cells in column Prix E85 using expression grel:value +\"000\"[0,5-value.length()]"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix Gazole",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.5590000000000002"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.559"
      }
    ],
    "description": "Mass edit cells in column Prix Gazole"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix Gazole",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.3820000000000001"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.382"
      }
    ],
    "description": "Mass edit cells in column Prix Gazole"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix Gazole",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.496999999999999"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.497"
      }
    ],
    "description": "Mass edit cells in column Prix Gazole"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix Gazole",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.593999999999999"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.594"
      }
    ],
    "description": "Mass edit cells in column Prix Gazole"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix Gazole",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.5190000000000001"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.519"
      }
    ],
    "description": "Mass edit cells in column Prix Gazole"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP95",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.488999999999999"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.489"
      }
    ],
    "description": "Mass edit cells in column Prix SP95"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP95",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.5070000000000001"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.507"
      }
    ],
    "description": "Mass edit cells in column Prix SP95"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP95",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.5390000000000001"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.539"
      }
    ],
    "description": "Mass edit cells in column Prix SP95"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP95",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.5590000000000002"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.559"
      }
    ],
    "description": "Mass edit cells in column Prix SP95"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP95",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.609999999999999"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.610"
      }
    ],
    "description": "Mass edit cells in column Prix SP95"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP95",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.6600000000000001"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.660"
      }
    ],
    "description": "Mass edit cells in column Prix SP95"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP98",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.4889999999999999"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.489"
      }
    ],
    "description": "Mass edit cells in column Prix SP98"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP98",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.5390000000000001"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.539"
      }
    ],
    "description": "Mass edit cells in column Prix SP98"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP98",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.5899999999999999"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.590"
      }
    ],
    "description": "Mass edit cells in column Prix SP98"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP98",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.597999999999999"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.598"
      }
    ],
    "description": "Mass edit cells in column Prix SP98"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP98",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.609999999999999"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.610"
      }
    ],
    "description": "Mass edit cells in column Prix SP98"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP98",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.6440000000000001"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.644"
      }
    ],
    "description": "Mass edit cells in column Prix SP98"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP98",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.6840000000000002"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.684"
      }
    ],
    "description": "Mass edit cells in column Prix SP98"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix SP98",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.6880000000000002"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.688"
      }
    ],
    "description": "Mass edit cells in column Prix SP98"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix GPLc",
    "expression": "value",
    "edits": [
      {
        "from": [
          "0.9490000000000001"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "0.949"
      }
    ],
    "description": "Mass edit cells in column Prix GPLc"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix GPLc",
    "expression": "value",
    "edits": [
      {
        "from": [
          "0.9500000000000001"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "0.950"
      }
    ],
    "description": "Mass edit cells in column Prix GPLc"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix E10",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.5590000000000002"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.559"
      }
    ],
    "description": "Mass edit cells in column Prix E10"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix E10",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.5899999999999999"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.590"
      }
    ],
    "description": "Mass edit cells in column Prix E10"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix E10",
    "expression": "value",
    "edits": [
      {
        "from": [
          "1.597999999999999"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "1.598"
      }
    ],
    "description": "Mass edit cells in column Prix E10"
  },
  {
    "op": "core/mass-edit",
    "engineConfig": {
      "facets": [],
      "mode": "row-based"
    },
    "columnName": "Prix E85",
    "expression": "value",
    "edits": [
      {
        "from": [
          "0.6990000000000001"
        ],
        "fromBlank": false,
        "fromError": false,
        "to": "0.699"
      }
    ],
    "description": "Mass edit cells in column Prix E85"
  }
]
````
