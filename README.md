# Medium Clone

This project is a clone of the popular blogging platform **Medium**, built using a modern tech stack to deliver a scalable, performant, and secure application.

---

## **Technologies Used**

1. **React**: For building the frontend user interface.
2. **Cloudflare Workers**: For the backend, enabling low-latency responses and scalability.
3. **Zod**: Validation library for robust data validation and type inference shared across the frontend and backend.
4. **TypeScript**: Static typing to improve developer productivity and code maintainability.
5. **Prisma**: ORM with connection pooling for seamless database interactions.
6. **PostgreSQL**: Database for reliable and scalable data storage.
7. **JWT**: Secure authentication mechanism.

---

## **Features**

- **Responsive User Interface**: Optimized for a seamless user experience on all devices.
- **Serverless Backend**: Built on Cloudflare Workers for high performance and scalability.
- **Data Validation and Type Safety**: Ensures consistency and prevents runtime errors.
- **Static Type-Checking**: Enhances development speed and reduces bugs.
- **Optimized Database Interactions**: Uses Prisma with connection pooling for performance improvements.
- **Secure Authentication**: JWT-based authentication for user security.

---

## **Common Module Deployment**

A common module has been implemented to:

- Export **Zod validation schemas** and type inference.
- Ensure consistency and reusability of validation logic across the application (frontend and backend).
