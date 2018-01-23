new Vue({
	el:'#taskApp',
	data:{
	 nameApp: 'GrabiTask',
	 tareas:[
	{
	 	titulo: 'tareas',
	 	hecho: true
	},
	{
	 	titulo: 'tareas 2',
	 	hecho: false
	},
	{
	 	titulo: 'tareas 3',
	 	hecho: false
	},
	]
},methods:{
	eliminarTarea:function(tarea){
	this.tareas.splice(this.tareas.indexOf(tarea),1)
}
}
})
