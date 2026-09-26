# VendeloYa — MVP con reconocimiento real de productos

## Requisitos
- Node.js 20+
- Una API key de OpenAI

## Ejecutar
1. Copia `.env.example` a `.env`.
2. Pon tu clave en `OPENAI_API_KEY`.
3. Ejecuta `npm install`.
4. Ejecuta `npm start`.
5. Abre `http://localhost:3000`.

La clave queda en el servidor y no se expone al navegador. La foto se envía al backend, que usa la Responses API con entrada de imagen para reconocer el producto y generar el anuncio.
