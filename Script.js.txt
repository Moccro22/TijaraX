function toggleUser(typ) {
  const angebote = document.getElementById('angebote');
  angebote.innerHTML = ''; // Leeren

  if (typ === 'einzel') {
    angebote.innerHTML = `
      <div><h3>iPhone 13</h3><p>Preis: 400€</p></div>
      <div><h3>Nike Schuhe</h3><p>Preis: 70€</p></div>
    `;
  } else if (typ === 'gross') {
    angebote.innerHTML = `
      <div><h3>iPhone 13 (10 Stück)</h3><p>Preis: 3500€</p></div>
      <div><h3>Nike Schuhe (50 Paar)</h3><p>Preis: 2800€</p></div>
    `;
  }
}