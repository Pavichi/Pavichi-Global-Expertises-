import React from "react"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button";

export default function Home() { return ( <main className="flex flex-col items-center justify-center p-4 space-y-8"> <header className="text-center"> <h1 className="text-4xl font-bold text-red-700">Pavichi Global</h1> <p className="text-lg text-green-600 mt-2"> Excellence | Global Presence | Ease | Integrity </p> </header>

<section className="max-w-3xl text-center">
    <h2 className="text-2xl font-semibold mb-2 text-green-500">Mission</h2>
    <p>
      To deliver high-quality and healthy food, fashion, and household products that meet the diverse needs of our customers, while maintaining sustainable practices and empowering local communities
    </p>
    <h2 className="text-2xl font-semibold mt-6 mb-2 text-green-500">Vision</h2>
    <p>
      To become a multinational brand revolutionizing food, fashion, and household products providing sustainable, high-quality goods that enrich the lives of people everywhere while fostering global impact and integrity.
    </p>
  </section>

  <section className="max-w-5xl w-full grid grid-cols-1 md:grid-cols-2 gap-6">
    <Card>
      <CardContent className="p-4">
        <h3 className="text-xl font-semibold text-red-700">EasyCook</h3>
        <p>
          Convenient, ready-to-use food products aimed at reducing post-harvest loss and promoting kitchen ease.
        </p>
      </CardContent>
    </Card>
    <Card>
      <CardContent className="p-4">
        <h3 className="text-xl font-semibold text-green-700">HealthyCook</h3>
        <p>
          Health-focused meals tailored to dietary needs, including options for different blood types, gut health, and lactose intolerance.
        </p>
      </CardContent>
    </Card>
  </section>

  <section className="max-w-3xl text-center">
    <h2 className="text-2xl font-semibold mt-8 mb-4 text-green-500">About Us</h2>
    <p>
      Pavichi Global is a visionary enterprise built to bridge the gap between convenience, health, and sustainability. With a presence in food processing, household essentials, and fashion, we are passionate about delivering quality with integrity.
    </p>
  </section>

  <section className="max-w-3xl text-center">
    <h2 className="text-2xl font-semibold mt-8 mb-4 text-green-500">Our Team</h2>
    <p>
      Our team is led by passionate entrepreneurs and experts dedicated to innovation, excellence, and a deep love for humanity. Our founder, inspired by a drive to solve real-life problems, brings structure, leadership, and compassion to everything we do.
    </p>
  </section>

  <section className="max-w-3xl text-center">
    <h2 className="text-2xl font-semibold mt-8 mb-4 text-green-500">Contact Us</h2>
    <p><strong>Phone/WhatsApp:</strong> +2347071597441</p>
    <p><strong>Facebook:</strong> Pavichi Global</p>
    <p><strong>Instagram:</strong> Pavichi Global</p>
    <p><strong>TikTok:</strong> Pavichi Global</p>
  </section>

  <section className="max-w-3xl text-center mt-10">
    <h2 className="text-xl font-semibold mb-2 text-red-700">Join Our Newsletter</h2>
    <input
      type="email"
      placeholder="Enter your email"
      className="p-2 border rounded-md w-full max-w-sm"
    />
    <Button className="mt-2 bg-green-600 hover:bg-green-700 text-white">
      Subscribe
    </Button>
  </section>
</main>

); }

