import React from 'react';
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Mail } from 'lucide-react';

export default function App() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-800 flex flex-col items-center p-6 space-y-10">
      
      {/* Header */}
      <header className="w-full max-w-4xl text-center mt-10">
        <h1 className="text-4xl font-bold mb-2">Hi, I'm Suzhen 👋</h1>
        <p className="text-lg text-gray-600">Aspiring Cybersecurity Analyst | Passionate about Tech & Art</p>
      </header>

      {/* About Section */}
      <Card className="w-full max-w-4xl shadow-xl">
        <CardContent className="p-6">
          <h2 className="text-2xl font-semibold mb-4">About Me</h2>
          <p>
            I am a motivated professional with experience in overseas purchasing and a strong passion for cybersecurity. Currently seeking entry-level roles in cybersecurity or penetration testing, where I can apply my skills in risk management and incident response.
          </p>
        </CardContent>
      </Card>

      {/* Projects Section */}
      <Card className="w-full max-w-4xl shadow-xl">
        <CardContent className="p-6">
          <h2 className="text-2xl font-semibold mb-4">Projects</h2>
          <ul className="list-disc list-inside space-y-2">
            <li>Cybersecurity Case Study: Ransomware Defense Simulation</li>
            <li>Procurement System Improvement Project – Reduced import lead times by 20%</li>
            <li>Chibi-style Art Portfolio (Mint Super Arts)</li>
          </ul>
        </CardContent>
      </Card>

      {/* Contact Section */}
      <Card className="w-full max-w-4xl shadow-xl">
        <CardContent className="p-6 text-center">
          <h2 className="text-2xl font-semibold mb-4">Contact</h2>
          <p>Feel free to reach out for opportunities or collaborations!</p>
          <Button className="mt-4" variant="default">
            <Mail className="mr-2 h-4 w-4" /> Email Me
          </Button>
        </CardContent>
      </Card>
    </div>
  );
}
