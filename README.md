 This WooCommerce-integrated chatbot is designed to transform post-sales customer support by combining automation and artificial intelligence to deliver fast, secure, and personalized assistance. By connecting directly to the WooCommerce database, the chatbot retrieves real-time order information—including shipping details and tracking numbers—after verifying the customer's identity through a strict email-based authentication system. This ensures maximum data security, preventing leaks of sensitive information.  

Beyond order management, the chatbot answers frequently asked questions about return policies, delivery times, and terms of service using a vector database that provides accurate, context-aware responses. If a request is too complex, the system seamlessly escalates it to a human operator via Telegram, guaranteeing no customer query goes unresolved.
# RU
Этот чат-бот, интегрированный с WooCommerce, предназначен для преобразования послепродажной поддержки клиентов за счет сочетания автоматизации и искусственного интеллекта для предоставления быстрой, безопасной и персонализированной помощи. Подключаясь напрямую к базе данных WooCommerce, чат-бот в режиме реального времени получает информацию о заказе, включая детали доставки и номера отслеживания, после проверки личности клиента с помощью строгой системы аутентификации на основе электронной почты. Это обеспечивает максимальную безопасность данных, предотвращая утечку конфиденциальной информации.  

Помимо управления заказами, чат-бот отвечает на часто задаваемые вопросы о правилах возврата, сроках доставки и условиях предоставления услуг, используя векторную базу данных, которая предоставляет точные ответы с учетом контекста. Если запрос слишком сложный, система легко передает его оператору-человеку через Telegram, гарантируя, что ни один запрос клиента не останется нерешенным.

#Launch step by step


# STEP 1
## Create Qdrant Collection
Change:
- QDRANTURL
- COLLECTION

# STEP 2
## Documents vectorization with Qdrant and Google Drive
Change:
- QDRANTURL
- COLLECTION
# STEP 3
- Add your Telegram CHAT_ID in the "human_assistance" tool
# STEP 4
The tracking code request is made through the most popular WooCommerce tracking plugin: "YITH WooCommerce Order & Shipment Tracking". The free version can be [downloaded here](https://wordpress.org/plugins/yith-woocommerce-order-tracking/)
- Create a new workflow and change URL in the node "Http Request" with your WooCommerce shop url
