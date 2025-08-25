// pages/index.js
import { useState } from "react";

export default function Home() {
  const [page, setPage] = useState("home"); // home, login, register, dashboard
  const [saldo, setSaldo] = useState(200);
  const [email, setEmail] = useState("");
  const [senha, setSenha] = useState("");
  const [nome, setNome] = useState("");

  const produtos = [
    { title: "Painel XIT", price: 50 },
    { title: "Painel Pro", price: 100 },
  ];

  const sacarPix = () => {
    const taxa = 10;
    if (saldo > taxa) {
      alert(`Pix realizado! Taxa descontada: R$${taxa}`);
      setSaldo(saldo - taxa);
    } else {
      alert("Saldo insuficiente!");
    }
  };

  const Navbar = () => (
    <nav className="bg-purple-700 p-4 flex justify-between items-center">
      <h1 className="text-xl font-bold">MeuEreemby</h1>
      <div className="space-x-4">
        <button onClick={() => setPage("home")}>Home</button>
        <button onClick={() => setPage("dashboard")}>Dashboard</button>
        <button onClick={() => setPage("login")}>Login</button>
        <button onClick={() => setPage("register")}>Registrar</button>
      </div>
    </nav>
  );

  const Footer = () => (
    <footer className="bg-purple-700 p-4 text-center mt-10">
      © 2025 MeuEreemby. Todos os direitos reservados.
    </footer>
  );

  const ProductCard = ({ title, price }) => (
    <div className="bg-gray-800 p-4 rounded-lg shadow-md hover:scale-105 transition-transform">
      <h2 className="font-bold text-lg">{title}</h2>
      <p className="mt-2">Preço: R${price}</p>
      <button className="mt-4 bg-purple-600 px-4 py-2 rounded hover:bg-purple-500">
        Comprar
      </button>
    </div>
  );

  const HomePage = () => (
    <main className="p-8 grid grid-cols-1 md:grid-cols-2 gap-6">
      {produtos.map((p, i) => (
        <ProductCard key={i} title={p.title} price={p.price} />
      ))}
    </main>
  );

  const LoginPage = () => (
    <main className="p-8 flex flex-col items-center">
      <h1 className="text-2xl font-bold mb-4">Login</h1>
      <input
        className="p-2 mb-2 rounded text-black"
        placeholder="Email"
        value={email}
        onChange={(e) => setEmail(e.target.value)}
      />
      <input
        type="password"
        className="p-2 mb-2 rounded text-black"
        placeholder="Senha"
        value={senha}
        onChange={(e) => setSenha(e.target.value)}
      />
      <button
        className="bg-purple-600 px-4 py-2 rounded hover:bg-purple-500"
        onClick={() => alert("Login simulado!")}
      >
        Entrar
      </button>
    </main>
  );

  const RegisterPage = () => (
    <main className="p-8 flex flex-col items-center">
      <h1 className="text-2xl font-bold mb-4">Registrar</h1>
      <input
        className="p-2 mb-2 rounded text-black"
        placeholder="Nome"
        value={nome}
        onChange={(e) => setNome(e.target.value)}
      />
      <input
        className="p-2 mb-2 rounded text-black"
        placeholder="Email"
        value={email}
        onChange={(e) => setEmail(e.target.value)}
      />
      <input
        type="password"
        className="p-2 mb-2 rounded text-black"
        placeholder="Senha"
        value={senha}
        onChange={(e) => setSenha(e.target.value)}
      />
      <button
        className="bg-purple-600 px-4 py-2 rounded hover:bg-purple-500"
        onClick={() => alert("Registro simulado!")}
      >
        Registrar
      </button>
    </main>
  );

  const DashboardPage = () => (
    <main className="p-8">
      <h1 className="text-2xl font-bold mb-4">Dashboard</h1>
      <p>Saldo atual: R${saldo}</p>
      <button
        className="mt-4 bg-purple-600 px-4 py-2 rounded hover:bg-purple-500"
        onClick={sacarPix}
      >
        Sacar Pix (com taxa)
      </button>
      <div className="mt-6">
        <a
          href="https://discord.gg/kGgkAZGbnU"
          target="_blank"
          className="text-blue-400 underline"
        >
          Suporte Discord
        </a>
      </div>
    </main>
  );

  return (
    <div className="bg-gray-900 min-h-screen text-white">
      <Navbar />
      {page === "home" && <HomePage />}
      {page === "login" && <LoginPage />}
      {page === "register" && <RegisterPage />}
      {page === "dashboard" && <DashboardPage />}
      <Footer />
    </div>
  );
}