let coffee = +prompt ("насыпьте в машину кофе", " ");
let water;
let sugar;

if (coffee == null || coffee == ''){
alert("отменено");
} else{
		
	water = +prompt ("налейте в машину воду", " ");
	if (water == null || water == ''){
	alert("отменено");
	} else{

		sugar = +prompt ("насыпьте в машину сахар", " ");
		if (sugar == null || sugar == ''){
		alert("отменено");
			} else{

				let check = prompt ("проверить?", "проверить");
				if (check == null || check == ''){
					alert("отменено");
				} else if (check == "проверить"){
					checkResaurses();
				} else { alert("некорректный ввод");}
			}
		}
	};


function checkResaurses(){
	if (coffee<5){
		alert("добавь кофейку");
	}

	if (water<5){
		alert ("добавь воды");
	}

	if (sugar<10){
		alert("добавь сахара");
	}

	else if (coffee>=5 && water>=5 && sugar>=10){
		let makeCoffee = prompt("введите \"приготовить\"", "приготовить");
		if (makeCoffee == "приготовить"){
					loanchCoffee();
				}
			}
		}
	
	function loanchCoffee(){
		let makeCoffee = coffee+water+sugar;
		alert("возьми кофе");
	}
