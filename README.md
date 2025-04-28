<h1 id="intro" align="center"></h1>

<script>
const text = "Hi there 👋, I'm Sok Limkhy - Backend Wizard & GUI Craftsman!";
let index = 0;

function typeWriter() {
    if (index < text.length) {
        document.getElementById("intro").innerHTML += text.charAt(index);
        index++;
        setTimeout(typeWriter, 70); // typing speed
    }
}
window.onload = typeWriter;
</script>
