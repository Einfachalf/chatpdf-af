
![Build and Deploy Full Stack ChatPDF Clone](https://github.com/Elliott-Chong/chatpdf-yt/assets/77007117/7fcee290-ca52-46ee-ae82-3490f505270b)



# Überblick

Willkommen beim "chatpdf-af" Projekt, einer umfassenden Chat-Anwendung mit PDF-Integration. Dieses Projekt ist darauf ausgelegt, ein nahtloses Chat-Erlebnis zu bieten, bei dem Benutzer PDF-Dateien hochladen, Chats um sie herum erstellen und mit einem KI-Assistenten interagieren können. Der KI-Assistent verwendet die OpenAI-API, um Antworten basierend auf dem Chat-Kontext zu generieren. Die Anwendung enthält auch eine Abonnement-Funktion, bei der Benutzer sich anmelden können, um Premium-Funktionen zu nutzen. Der Abonnementprozess wird mit Stripe für Zahlungen und Webhooks für die Ereignisverarbeitung gehandhabt.

# Technologien und Frameworks

- Next.js
- React
- TypeScript
- Tailwind CSS
- Clerk
- Drizzle ORM
- PostgreSQL
- AWS SDK
- OpenAI API
- Stripe
- Axios
- Pinecone
- Drizzle-kit
- OpenAI Edge
- Neon Database Serverless
- Drizzle-orm/neon-http
- @tanstack/react-query
- @clerk/nextjs
- clsx
- tailwind-merge

# Installation

Befolgen Sie die unten stehenden Schritte, um das Projekt zu installieren und einzurichten:

1. **Klonen Sie das Repository**

   Öffnen Sie Ihr Terminal und führen Sie den folgenden Befehl aus:

   ```bash
   git clone https://github.com/Einfachalf/chatpdf-af.git
   ```

2. **Navigieren Sie zum Projektverzeichnis**

   ```bash
   cd chatpdf-af
   ```

3. **Installieren Sie Node.js**

   Das Projekt erfordert Node.js Version 13.4.19 oder später. Sie können es von [hier](https://nodejs.org/en/download/) herunterladen.

4. **Installieren Sie die erforderlichen Abhängigkeiten**

   Führen Sie den folgenden Befehl aus, um alle erforderlichen Abhängigkeiten zu installieren:

   ```bash
   npm install
   ```

   Dies wird alle in der `package.json`-Datei aufgeführten Abhängigkeiten installieren, einschließlich Next.js, React, React DOM, Axios, Stripe, Tailwind CSS und andere spezifische Abhängigkeiten wie "@aws-sdk/client-s3" und "@clerk/nextjs".

5. **Richten Sie Umgebungsvariablen ein**

    Erstellen Sie eine `.env`-Datei im Stammverzeichnis Ihres Projekts und fügen Sie die erforderlichen Umgebungsvariablen hinzu.

   - database_URL: enthält die URL für die Datenbankverbindung.
- NEXT_PUBLIC_S3_bucket_name: enthält den Namen des S3-Buckets, in dem die Dateien gespeichert werden sollen.
- NEXT_PUBLIC_S3_access_key_id: enthält die Zugriffs-Schlüssel-ID für den S3-Bucket.
- NEXT_PUBLIC_S3_secret_access_key: enthält den geheimen Zugriffsschlüssel für den S3-Bucket.
- NEXT_PUBLIC_Clerk_frontend_api: enthält die Front-End-API-URL für Clerk, einen Dienst für die Benutzerauthentifizierung.
- NEXT_PUBLIC_Clerk_sign_in_redirect: enthält die URL, zu der umgeleitet wird, nachdem sich ein Benutzer angemeldet hat.
- NEXT_PUBLIC_Clerk_sign_up_redirect: enthält die URL, zu der umgeleitet wird, nachdem ein Benutzer sich registriert hat.
- NEXT_PUBLIC_Clerk_signed_out_redirect: enthält die URL, zu der umgeleitet wird, nachdem sich ein Benutzer abgemeldet hat.
- NEXT_PUBLIC_Clerk_verification_email_redirect: enthält die URL, zu der umgeleitet wird, nachdem ein Benutzer seine E-Mail-Adresse verifiziert hat.

7. **Führen Sie das Projekt aus**

    Jetzt können Sie das Projekt mit dem folgenden Befehl ausführen:

    ```bash
    npm run dev
    ```

    Öffnen Sie [http://localhost:3000](http://localhost:3000) mit Ihrem Browser, um das Ergebnis zu sehen.
```

Diese Datei gibt einen Überblick über das Projekt, einschließlich der verwendeten Technologien und Frameworks, und Anweisungen zur Installation und Ausführung des Projekts.


