/* ===== Velusa Menu Data ===== */

const drinks = [
    {
        name: "Velusa Matcha Cloud",
        desc: "16oz PET • pink straw • cloud foam",
        img: "assets/drinks/matcha_cloud.png"
    },
    {
        name: "Rose‑Gold Strawberry Matcha",
        desc: "Layered blush aesthetic",
        img: "assets/drinks/strawberry_matcha.png"
    }
];

const pastries = [
    {
        name: "Miffy Cream Puff",
        desc: "Uniform color • filled center",
        img: "assets/pastries/miffy_puff.png"
    },
    {
        name: "Milly Custard Bun",
        desc: "Soft matte finish",
        img: "assets/pastries/milly_bun.png"
    }
];

/* ===== Render Function ===== */

function renderMenu(items, containerId) {
    const container = document.getElementById(containerId);
    container.innerHTML = items.map(item => `
        <div class="menu-card">
            <img src="${item.img}" class="menu-img">
            <div class="menu-name">${item.name}</div>
            <div class="menu-desc">${item.desc}</div>
        </div>
    `).join("");
}

/* ===== Initialize ===== */

renderMenu(drinks, "drinkGrid");
renderMenu(pastries, "pastryGrid");
