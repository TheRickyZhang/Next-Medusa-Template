# Medusa Next.js Starter Template with Bun

An all-in-one modern ecommerce template powered by **Next.js**, **Medusa**, and **Bun**. Tired of paying for expensive store backends? This bridges the gap between most free templates and production.
## Quickstart

### Prerequisites

Ensure you have a Medusa server running locally on port `9000`. For quick setup, run:
```bash
npx create-medusa-app@latest
```

### Installation

1. **Clone the Repository**:
   ```bash
   git clone <url>
   cd next-medusa-template
   ```

2. **Set up Environment Variables**:
   ```bash
   mv .env.template .env.local
   ```
   Populate `.env.local` with your credentials, including:
   ```env
   NEXT_PUBLIC_STRIPE_KEY=<your-stripe-public-key>
   ```

3. **Install Dependencies**:
   ```bash
   bun install
   ```

4. **Start Development Server**:
   ```bash
   bun dev
   ```

5. **Access Your Store**:
   Visit [http://localhost:8000](http://localhost:8000).

---

## Payment Integration

Add your Stripe Public Key to `.env.local`:
```env
NEXT_PUBLIC_STRIPE_KEY=<your-stripe-public-key>
```

# TODO: Explain how to populate all these environment variables since it can be a bit confusing
---