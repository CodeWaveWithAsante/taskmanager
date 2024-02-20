@import url("https://fonts.googleapis.com/css2?family=Nunito+Sans:opsz,wght@6..12,200;6..12,300;6..12,400;6..12,500;6..12,600;6..12,700;6..12,800;6..12,900;6..12,1000&display=swap");

@tailwind base;
@tailwind components;
@tailwind utilities;

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;

  font-family: "Nunito Sans", sans-serif;
}

.cell {
  display: inline-block;
  width: 49%;
  text-align: center;
}

.circle {
  display: inline-block;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background: rgba(203, 37, 156, 0.671);
  box-shadow: 4px -40px 60px 5px rgb(40, 37, 203) inset;
}

.rotate-in-up-left {
  animation: rotate-in-up-left 2s ease infinite;
}

@keyframes rotate-in-up-left {
  0% {
    transform-origin: left bottom;
    transform: rotate(90deg);
    opacity: 0;
  }
  100% {
    transform-origin: left bottom;
    transform: rotate(0);
    opacity: 1;
  }
}

.form-container {
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  border-radius: 10px;
  box-sizing: border-box;
}

/* Custom Scrollbar Styles */
/* Track */
::-webkit-scrollbar {
  width: 8px;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background-color: #807c7c;
  border-radius: 6px;
  display: none;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background-color: #302f2f;
}

/* Track */
::-webkit-scrollbar-track {
  background: transparent;
}

.dots-container {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
  width: 100%;
  margin-bottom: 5px;
}

.dot {
  height: 12px;
  width: 12px;
  margin-right: 10px;
  border-radius: 10px;
  background-color: #fff;
  animation: pulse 1.5s infinite ease-in-out;
}

.dot:last-child {
  margin-right: 0;
}

.dot:nth-child(1) {
  animation-delay: -0.3s;
}

.dot:nth-child(2) {
  animation-delay: -0.1s;
}

.dot:nth-child(3) {
  animation-delay: 0.1s;
}

@keyframes pulse {
  0% {
    transform: scale(0.8);
    background-color: #b3d4fc;
    box-shadow: 0 0 0 0 rgba(178, 212, 252, 0.7);
  }

  50% {
    transform: scale(1.2);
    background-color: #4b79e4;
    box-shadow: 0 0 0 10px rgba(178, 212, 252, 0);
  }

  100% {
    transform: scale(0.8);
    background-color: #2584f8;
    box-shadow: 0 0 0 0 rgba(178, 212, 252, 0.7);
  }
}
