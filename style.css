// Mengambil elemen input pencarian dan semua kartu penyakit
const searchInput = document.getElementById('searchInput');
const diseaseCards = document.querySelectorAll('.disease-card');

// Menambahkan event listener saat pengguna mengetik di kolom pencarian
searchInput.addEventListener('keyup', function (event) {
    const keyword = event.target.value.toLowerCase();

    // Memeriksa setiap kartu penyakit
    diseaseCards.forEach(card => {
        const diseaseName = card.getAttribute('data-name');

        // Jika nama penyakit cocok dengan yang diketik, tampilkan; jika tidak, sembunyikan
        if (diseaseName.includes(keyword)) {
            card.style.display = 'block';
        } else {
            card.style.display = 'none';
        }
    });
});
