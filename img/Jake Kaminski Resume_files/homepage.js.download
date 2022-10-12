
function openNav(){
    document.getElementById('mySideNav').style.width="250px";  
    changeOpenBtnVisibility(true)    
}
function closeNav(){
    document.getElementById('mySideNav').style.width="0"
    changeOpenBtnVisibility(false) 
}
function changeOpenBtnVisibility(hide = false){
    var x = document.getElementById("openNavBtn");
    if (hide) {
            x.style.visibility = "hidden";    
    } else {
        setTimeout(() => {
            x.style.visibility = "visible";
        }, 250);
    }
}
