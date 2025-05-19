# Aakash-Hospital// Single-page professional hospital website with full bilingual content
import React from "react";

export default function AakashHospital() {
  return (
    <div className="font-sans bg-gray-50 text-gray-900">
      <header className="bg-red-600 text-white p-6 shadow-md">
        <div className="container mx-auto flex flex-col md:flex-row justify-between items-center">
          <h1 className="text-3xl font-bold">Aakash Hospital</h1>
          <p className="text-sm mt-2 md:mt-0">📍 Near Sanjay Chowk, Deoband Road, Nanauta, Saharanpur, UP</p>
        </div>
      </header>

      <main className="container mx-auto px-4 py-8">
        {/* Hero Section */}
        <section className="mb-12 text-center">
          <h2 className="text-4xl font-bold mb-4">Welcome to Aakash Hospital / आकाक्ष अस्पताल में आपका स्वागत है</h2>
          <p className="text-lg">Your Health, Our Priority / आपका स्वास्थ्य, हमारी प्राथमिकता</p>
          <img src="/hospital-image.jpg" alt="Aakash Hospital" className="mx-auto my-6 rounded-lg shadow-md max-h-[400px]" />
        </section>

        {/* About */}
        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-3">About Us / हमारे बारे में</h3>
          <p>
            Established in 2024, Aakash Hospital is a modern multispecialty healthcare center dedicated to providing quality and affordable healthcare in Nanauta, Saharanpur. We are empaneled under Ayushman Bharat Yojana to serve economically weaker sections. <br />
            आकाक्ष अस्पताल, 2024 में स्थापित, नानौता में स्थित एक आधुनिक मल्टीस्पेशलिटी हेल्थकेयर सेंटर है जो गुणवत्तापूर्ण और किफायती चिकित्सा सेवाएं प्रदान करता है। हम आयुष्मान भारत योजना के अंतर्गत सूचीबद्ध हैं।
          </p>
        </section>

        {/* Departments */}
        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-3">Departments & Facilities / विभाग और सुविधाएं</h3>
          <ul className="list-disc ml-6 space-y-1">
            <li>General Medicine / सामान्य चिकित्सा</li>
            <li>General Surgery / सामान्य शल्य चिकित्सा</li>
            <li>Orthopedics / हड्डी रोग</li>
            <li>Gynecology & Obstetrics / स्त्री रोग एवं प्रसूति</li>
                    <li>Pathology Lab / पैथोलॉजी लैब</li>
            <li>Pharmacy / फार्मेसी</li>
            <li>Emergency & IPD/OPD Services / आपातकालीन और इनडोर/आउटडोर सेवाएं</li>
          </ul>
        </section>

        {/* Doctors */}
        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-3">Our Doctors / हमारे डॉक्टर</h3>
          <ul className="space-y-2">
            <li><strong>Dr. Ravi Sharma</strong> – MBBS, MD (General Medicine)</li>
            <li><strong>Dr. Pooja Verma</strong> – MS (Gynaecology)</li>
            <li><strong>Dr. Akash Singh</strong> – MS (Orthopedics)</li>
            <li><strong>Dr. Neha Jain</strong> – MD (Pediatrics)</li>
          </ul>
        </section>

        {/* Ayushman Bharat */}
        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-3">Ayushman Bharat Yojana / आयुष्मान भारत योजना</h3>
          <p>
            Aakash Hospital is empaneled under Ayushman Bharat – PM-JAY to provide free and cashless treatment to eligible families. Patients can access benefits by showing their Ayushman card at our hospital. <br />
            आकाक्ष अस्पताल आयुष्मान भारत – प्रधानमंत्री जन आरोग्य योजना के तहत सूचीबद्ध है, जहां पात्र परिवारों को मुफ्त और कैशलेस इलाज की सुविधा मिलती है। मरीज अपने आयुष्मान कार्ड के माध्यम से लाभ ले सकते हैं।
          </p>
        </section>

        {/* Appointment Form */}
        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-3">Book Appointment / अपॉइंटमेंट बुक करें</h3>
          <form className="space-y-4 max-w-lg mx-auto">
            <input type="text" placeholder="Full Name / नाम" className="w-full p-3 border rounded" />
            <input type="tel" placeholder="Phone / फ़ोन नंबर" className="w-full p-3 border rounded" />
            <input type="text" placeholder="Department / विभाग" className="w-full p-3 border rounded" />
            <input type="date" className="w-full p-3 border rounded" />
            <textarea placeholder="Message / संदेश" className="w-full p-3 border rounded"></textarea>
            <button className="bg-red-600 text-white px-6 py-3 rounded">Submit / सबमिट करें</button>
          </form>
        </section>

        {/* Testimonials */}
        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-3">Patient Testimonials / मरीजों की राय</h3>
          <blockquote className="italic border-l-4 border-red-600 pl-4">“Very caring staff and clean facility. Best in the area!” – Sunita Devi</blockquote>
          <blockquote className="italic border-l-4 border-red-600 pl-4 mt-4">“Free treatment under Ayushman Bharat helped my family. Thank you.” – Rajeev</blockquote>
        </section>

        {/* Contact */}
        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-3">Contact Us / संपर्क करें</h3>
          <p>📍 Near Sanjay Chowk, Deoband Road, Nanauta, Saharanpur, UP</p>
          <p>📞 +91-8430999900</p>
          <p>✉️ aakashhospitalnan5986@gmail.com</p>
        </section>
      </main>

      <footer className="bg-gray-100 py-6 text-center text-sm text-gray-700">
        <p>&copy; 2025 Aakash Hospital. All rights reserved.</p>
      </footer>
    </div>
  );
}
