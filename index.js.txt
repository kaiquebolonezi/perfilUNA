document.addEventListener('DOMContentLoaded', function() {
    const greeting = document.querySelector('header p');
    const hour = new Date().getHours();
    if (hour < 12) {
        greeting.textContent = 'Bom dia! Sou Kaique, profissional de Segurança da Informação';
    } else if (hour < 18) {
        greeting.textContent = 'Boa tarde! Sou Kaique, profissional de Segurança da Informação';
    } else {
        greeting.textContent = 'Boa noite! Sou Kaique, profissional de Segurança da Informação';
    }
});
