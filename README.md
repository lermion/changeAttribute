# changeAttribute

function changeAttribute(){
			var p = document.getElementsByTagName("p");
			for(var i = 0; i < p.length; i++){
				if(p[i].getAttribute("align") === "left"){
					p[i].setAttribute("align", "right");
				}else{
					p[i].setAttribute("align", "left");
				}
			}
		}
