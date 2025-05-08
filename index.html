<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no" />
<title>Pembayaran Mewah - Dana, QRIS & GoPay</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@400;600&display=swap');

  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(135deg, #1f1c2c, #928dab);
    color: #f0e9e3;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    height: 600px;
    max-width: 350px;
    margin-left: auto;
    margin-right: auto;
    padding: 20px 15px;
  }
  h1 {
    font-family: 'Playfair Display', serif;
    font-weight: 700;
    font-size: 2.2rem;
    margin-bottom: 0.2em;
    text-align: center;
    text-shadow:
      2px 2px 6px rgba(255, 255, 255, 0.15),
      -2px -2px 6px rgba(0, 0, 0, 0.3);
  }
  p.subtitle {
    font-weight: 600;
    font-size: 1rem;
    letter-spacing: 1.2px;
    margin-bottom: 2rem;
    color: #ddd6d6;
    text-align: center;
    text-transform: uppercase;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.4);
  }
  .payment-container {
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 20px;
  }
  .payment-card {
    background: rgba(255, 255, 255, 0.1);
    border: 1px solid rgba(255, 255, 255, 0.25);
    backdrop-filter: blur(10px);
    border-radius: 16px;
    box-shadow:
      0 4px 15px rgba(0,0,0,0.4),
      inset 0 0 10px rgba(255, 255, 255, 0.1);
    padding: 20px 25px;
    cursor: pointer;
    transition:
      transform 0.3s ease,
      box-shadow 0.3s ease,
      background-color 0.3s ease;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
  }
  .payment-card:hover {
    transform: translateY(-6px);
    box-shadow:
      0 8px 30px rgba(255, 255, 255, 0.35),
      inset 0 0 15px rgba(255, 255, 255, 0.2);
    background: rgba(255, 255, 255, 0.17);
  }
  .payment-text {
    font-weight: 600;
    font-size: 1.6rem;
    color: #fff;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.6);
  }
  .payment-number {
    font-weight: 400;
    font-size: 1rem;
    color: #cfc9d1;
    margin-top: 6px;
    letter-spacing: 1px;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
  }
  /* QRIS toggle button */
  #qris-button {
    margin: 10px auto 0 auto;
    display: none;
    background: #8e7cc3;
    border: none;
    color: white;
    padding: 11px 34px;
    border-radius: 25px;
    font-weight: 600;
    font-size: 1.1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
    box-shadow: 0 4px 12px #7f67b8aa;
  }
  #qris-button:hover {
    background: #b19de3;
  }
  /* QRIS image container */
  #qris-image-container {
    margin: 20px auto 0 auto;
    width: 220px;
    max-width: 90vw;
    border-radius: 16px;
    box-shadow:
      0 8px 20px rgba(142,124,195,0.7),
      inset 0 0 15px rgba(255, 255, 255, 0.13);
    overflow: hidden;
    display: none;
  }
  #qris-image-container img {
    width: 100%;
    height: auto;
    display: block;
  }
  /* Modal styles */
  .modal {
    position: fixed;
    top: 0; left: 0; right: 0; bottom: 0;
    background: rgba(0,0,0,0.75);
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.4s ease;
    z-index: 1100;
  }
  .modal.show {
    opacity: 1;
    pointer-events: all;
  }
  .modal-content {
    background: #2c2940;
    border-radius: 12px;
    padding: 25px 30px;
    max-width: 320px;
    width: 90%;
    box-shadow: 0 0 28px #8e7cc3aa;
    color: #fff;
    text-align: center;
  }
  .modal-content h2 {
    margin: 0 0 15px;
    font-family: 'Playfair Display', serif;
    font-weight: 700;
  }
  .modal-content p {
    margin: 10px 0 20px;
    font-size: 1rem;
    line-height: 1.4;
  }
  .modal-close {
    background: #8e7cc3;
    border: none;
    color: white;
    padding: 10px 24px;
    border-radius: 25px;
    font-weight: 600;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
  .modal-close:hover {
    background: #b19de3;
  }
  /* Responsive text scaling for small devices */
  @media (max-width: 350px) {
    h1 {
      font-size: 1.6rem;
    }
    .payment-text {
      font-size: 1.4rem;
    }
    .payment-number {
      font-size: 0.9rem;
    }
    #qris-button {
      font-size: 1rem;
      padding: 10px 28px;
    }
    #qris-image-container {
      width: 180px;
    }
  }
</style>
</head>
<body>
  <h1>All Payment</h1>
  <p class="subtitle">Pilih Metode Pembayaran</p>
  <div class="payment-container">
    <div class="payment-card" data-method="Dana" tabindex="0" role="button" aria-label="Bayar dengan Dana">
      <span class="payment-text">Dana</span>
      <span class="payment-number">0857-8856-8549</span>
    </div>
    <div class="payment-card" id="qris-card" tabindex="0" role="button" aria-label="Bayar dengan QRIS">
      <span class="payment-text">QRIS</span>
    </div>
    <button id="qris-button" aria-expanded="false" aria-controls="qris-image-container">Tampilkan QRIS</button>
    <div id="qris-image-container" aria-hidden="true">
      <img src="https://files.catbox.moe/o33aoc.jpg" alt="Kode QRIS untuk pembayaran" />
    </div>
    <div class="payment-card" data-method="GoPay" tabindex="0" role="button" aria-label="Bayar dengan GoPay">
      <span class="payment-text">GoPay</span>
      <span class="payment-number">0857-8856-8549</span>
    </div>
  </div>

  <div class="modal" id="modal">
    <div class="modal-content" role="dialog" aria-modal="true" aria-labelledby="modal-title">
      <h2 id="modal-title">Metode Pembayaran</h2>
      <p id="modal-message"></p>
      <button class="modal-close" id="modal-close">Tutup</button>
    </div>
  </div>

<script>
  const paymentCards = document.querySelectorAll('.payment-card[data-method]');
  const modal = document.getElementById('modal');
  const modalMessage = document.getElementById('modal-message');
  const modalClose = document.getElementById('modal-close');

  // Dana and GoPay payment cards show modal
  paymentCards.forEach(card => {
    card.addEventListener('click', () => {
      const method = card.getAttribute('data-method');
      openModal(method);
    });
    card.addEventListener('keypress', (e) => {
      if (e.key === 'Enter' || e.key === ' ') {
        e.preventDefault();
        const method = card.getAttribute('data-method');
        openModal(method);
      }
    });
  });

  function openModal(method) {
    modalMessage.textContent = 'Anda memilih metode pembayaran: ' + method;
    modal.classList.add('show');
  }
  function closeModal() {
    modal.classList.remove('show');
  }

  modalClose.addEventListener('click', closeModal);

  // Close modal on outside click
  modal.addEventListener('click', (e) => {
    if (e.target === modal) {
      closeModal();
    }
  });

  // Accessibility: Close modal with Escape key
  window.addEventListener('keydown', (e) => {
    if (e.key === 'Escape' && modal.classList.contains('show')) {
      closeModal();
    }
  });

  // QRIS card toggle behavior
  const qrisCard = document.getElementById('qris-card');
  const qrisButton = document.getElementById('qris-button');
  const qrisImageContainer = document.getElementById('qris-image-container');

  qrisCard.addEventListener('click', () => {
    // Show the QRIS button when QRIS card clicked (if hidden)
    if (qrisButton.style.display === 'none' || qrisButton.style.display === '') {
      qrisButton.style.display = 'block';
      qrisButton.focus();
    }
  });
  qrisCard.addEventListener('keypress', (e) => {
    if (e.key === 'Enter' || e.key === ' ') {
      e.preventDefault();
      if (qrisButton.style.display === 'none' || qrisButton.style.display === '') {
        qrisButton.style.display = 'block';
        qrisButton.focus();
      }
    }
  });

  // QRIS button toggles QR code image show/hide
  qrisButton.addEventListener('click', () => {
    if (qrisImageContainer.style.display === 'none' || qrisImageContainer.style.display === '') {
      qrisImageContainer.style.display = 'block';
      qrisButton.textContent = 'Sembunyikan QRIS';
      qrisButton.setAttribute('aria-expanded', 'true');
      qrisImageContainer.setAttribute('aria-hidden', 'false');
      // Scroll QRIS image into view smoothly for better user experience
      qrisImageContainer.scrollIntoView({behavior: 'smooth', block: 'center'});
    } else {
      qrisImageContainer.style.display = 'none';
      qrisButton.textContent = 'Tampilkan QRIS';
      qrisButton.setAttribute('aria-expanded', 'false');
      qrisImageContainer.setAttribute('aria-hidden', 'true');
    }
  });

  // On page load hide the QRIS button and image container
  window.addEventListener('load', () => {
    qrisButton.style.display = 'none';
    qrisImageContainer.style.display = 'none';
    qrisButton.textContent = 'Tampilkan QRIS';
    qrisButton.setAttribute('aria-expanded', 'false');
    qrisImageContainer.setAttribute('aria-hidden', 'true');
  });
</script>
</body>
</html>
</content>
</create_file>
      
