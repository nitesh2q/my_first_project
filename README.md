# my_first_project
import React from "react";
import image from "../../../assets/santara-icon.png";

const NavBar = () => {
  return (
    <div className="w-full h-20 flex items-center justify-between bg-transperent px-8 ">
      {/* Logo Section */}
      <div className="relative  border-2 ">
        <div className="  h-20 w-25  border-2">
        <img src={image} alt="Santara Logo" className=" w-30 h-24 mt-0 ml-0" />
        </div>
        <div>
          {/* <h1 className="text-orange-600 text-lg font-bold">SANTARA</h1>
          <p className="text-white text-sm tracking-widest">WEALTH MANAGEMENT</p> */}
        </div>
      </div>

      {/* Navigation Links */}
      <ul className="flex space-x-10 text-white font-medium text-xl px-10">
        <li className="hover:text-orange-500 cursor-pointer">All Pages</li>
        <li className="hover:text-orange-500 cursor-pointer">Home</li>
        <li className="hover:text-orange-500 cursor-pointer">About</li>
       
      </ul>
      <button className="relative bg-white text-black px-7 py-2 rounded-full overflow-hidden font-medium group">
  <span className="absolute inset-0 bg-orange-500 transform -translate-x-full group-hover:translate-x-0 transition-transform duration-300"></span>
  <span className="relative z-10">Schwab Login</span>
</button>

    </div>
  );
};

export default NavBar;

