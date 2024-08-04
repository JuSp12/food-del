config/db.js

import mongoose from "mongoose";

export const connectDB = async () => {
    await mongoose.connect('YOUR PATH TO MONGOOSE').then(()=> console.log("DB Connected"));
}