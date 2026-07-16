# Gold-Tadel-AI
Make it to be able to answer questions to be able too create image to be able to create videos to be able to do children assignments and to be able to give ideas
it should be able to do all what chat gbt can do
function sendMessage(){

let message=document.getElementById("message").value;

let chat=document.getElementById("chat");

chat.innerHTML+=`
<p><b>You:</b> ${message}</p>
`;

chat.innerHTML+=`
<p><b>Gold Tadel AI:</b> Hello! I'm still under development.</p>
`;

document.getElementById("message").value="";
}
