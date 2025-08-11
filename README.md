import React from "react";

const NATURE_IMAGE_URL =
  "https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80"; // Example nature image (replace with your own AI-generated image)

export default function Homepage() {
  return (
    <div style={{ fontFamily: "sans-serif", background: "#f8f9fa", minHeight: "100vh" }}>
      {/* Header */}
      <header style={{
        background: "#fff",
        boxShadow: "0 2px 8px rgba(0,0,0,0.05)",
        padding: "24px 0",
        textAlign: "center"
      }}>
        <h1 style={{
          margin: 0,
          fontWeight: 700,
          fontSize: "2.5rem",
          letterSpacing: "-1px"
        }}>WrapMarket Shipora</h1>
        <p style={{
          margin: "8px 0 0 0",
          color: "#666",
          fontSize: "1.25rem"
        }}>
          Sell, Ship, and Grow with Ease
        </p>
      </header>
      {/* Main Content */}
      <main style={{
        maxWidth: "980px",
        margin: "40px auto",
        background: "#fff",
        borderRadius: "16px",
        boxShadow: "0 8px 24px rgba(0,0,0,0.08)",
        padding: "32px",
        display: "flex",
        flexWrap: "wrap",
        alignItems: "center",
        gap: "32px"
      }}>
        <div style={{ flex: "1 1 350px", minWidth: "350px" }}>
          <h2 style={{ fontSize: "2rem", marginBottom: "16px" }}>
            Simple. Smart. Seamless.
          </h2>
          <p style={{ fontSize: "1.1rem", color: "#444", marginBottom: "24px" }}>
            Discover the fastest way to manage your store, shipping, and customer experience. 
            Streamline your workflow and boost your business with Shipora!
          </p>
          <button style={{
            background: "#3b82f6",
            color: "#fff",
            border: "none",
            borderRadius: "8px",
            padding: "14px 32px",
            fontSize: "1.1rem",
            fontWeight: 600,
            cursor: "pointer",
            boxShadow: "0 2px 8px rgba(59,130,246,0.15)"
          }}>
            Get Started
          </button>
        </div>
        <div style={{ flex: "1 1 350px", minWidth: "350px", textAlign: "center" }}>
          <img
            src={NATURE_IMAGE_URL}
            alt="Nature AI Generated"
            style={{
              width: "100%",
              maxWidth: "380px",
              borderRadius: "16px",
              boxShadow: "0 4px 16px rgba(0,0,0,0.08)"
            }}
          />
        </div>
      </main>
      {/* Footer */}
      <footer style={{
        textAlign: "center",
        color: "#888",
        fontSize: "0.95rem",
        margin: "36px 0 16px 0"
      }}>
        &copy; 2025 Shipora by WrapMarket. All rights reserved.
      </footer>
    </div>
  );
}
