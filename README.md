## Cancer

    [{
	"$project" : { "Type" : "Local Project",
		"Name" : "Cancer",
		"Description" : "Sistema de Registro y acceso mediante diferentes proveedores sociales.",
		"From" : { "$django" : { "Version" : "1.8.2"},
				   "$BSP" : {"Version" : "0.1.1"},
				 },
		"Group" : { "G" : "Public", "B" : "Private", "H" : "Deploy"},
		"_id" : 7
	},
    }]

