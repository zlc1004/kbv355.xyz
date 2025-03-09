# kbv355.xyz

## kobosh

# koboshjoei

[kobosh](https://kobosh.com)

# black people

<div class="switch">
  <input id="toggle" type="checkbox" />
  <label class="toggle" for="toggle">
    <i></i>
  </label>
</div>
 
.switch {
  position: relative;
  width: 210px;
  height: 50px;
  box-sizing: border-box;
  padding: 3px;
  background: #0d0d0d;
  border-radius: 6px;
  box-shadow:
    inset 0 1px 1px 1px rgba(0, 0, 0, 0.5),
    0 1px 0 0 rgba(255, 255, 255, 0.1);
}
.switch input[type="checkbox"] {
  position: absolute;
  z-index: 1;
  width: 100%;
  height: 100%;
  opacity: 0;
  cursor: pointer;
}
.switch input[type="checkbox"] + label {
  position: relative;
  display: block;
  left: 0;
  width: 50%;
  height: 100%;
  background: #1b1c1c;
  border-radius: 3px;
  box-shadow: inset 0 1px 0 0 rgba(255, 255, 255, 0.1);
  transition: all 0.5s ease-in-out;
}
.switch input[type="checkbox"] + label:before {
  content: "";
  display: inline-block;
  width: 5px;
  height: 5px;
  margin-left: 10px;
  background: #fff;
  border-radius: 50%;
  vertical-align: middle;
  box-shadow:
    0 0 5px 2px rgba(165, 15, 15, 0.9),
    0 0 3px 1px rgba(165, 15, 15, 0.9);
  transition: all 0.5s ease-in-out;
}
.switch input[type="checkbox"] + label:after {
  content: "";
  display: inline-block;
  width: 0;
  height: 100%;
  vertical-align: middle;
}
.switch input[type="checkbox"] + label i {
  display: block;
  position: absolute;
  top: 50%;
  left: 50%;
  width: 3px;
  height: 24px;
  margin-top: -12px;
  margin-left: -1.5px;
  border-radius: 2px;
  background: #0d0d0d;
  box-shadow: 0 1px 0 0 rgba(255, 255, 255, 0.3);
}
.switch input[type="checkbox"] + label i:before,
.switch input[type="checkbox"] + label i:after {
  content: "";
  display: block;
  position: absolute;
  width: 100%;
  height: 100%;
  border-radius: 2px;
  background: #0d0d0d;
  box-shadow: 0 1px 0 0 rgba(255, 255, 255, 0.3);
}
.switch input[type="checkbox"] + label i:before {
  left: -7px;
}
.switch input[type="checkbox"] + label i:after {
  left: 7px;
}
.switch input[type="checkbox"]:checked + label {
  left: 50%;
}
.switch input[type="checkbox"]:checked + label:before {
  box-shadow:
    0 0 5px 2px rgba(15, 165, 70, 0.9),
    0 0 3px 1px rgba(15, 165, 70, 0.9);
}

