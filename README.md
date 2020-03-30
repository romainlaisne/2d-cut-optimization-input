# 2d cut optimization example (input for cut-api.xom)
Input example to be used with [cut-api.com](cut-api.com) API

```json
  {
	"payload": {
		"nb demand pieces": 2,
		"pieces": [{
			"length": 500,
			"with": 600,
			"canrotate": 1,
			"external_id": 0,
			"priority": 0
		}, {
			"length": 500,
			"with": 600,
			"canrotate": 1,
			"external_id": 1,
			"priority": 0
		}],
		"nb inventory pieces": 2,
		"inventory": [{
			"length": 2000,
			"width": 3000,
			"TrimTop": 0,
			"TrimLeft": 0,
			"TrimBottom": 0,
			"TrimRight": 0,
			"external_ID": 0,
			"priority": 0,
			"num_holes": 0
		}, {
			"length": 1000,
			"width": 3000,
			"TrimTop": 0,
			"TrimLeft": 0,
			"TrimBottom": 0,
			"TrimRight": 0,
			"external_ID": 1,
			"priority": 0,
			"num_holes": 0
		}]
	},
	"optimizationType": 0,
	"optimizationLevel": 0,
	"bladeThickness": 10
}
  </code>
