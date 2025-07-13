# 🔍 101 Sequence Detector (Mealy FSM)

This is a simple Verilog project that detects the binary sequence `101` using a **Mealy finite state machine (FSM)**. It’s a classic example to understand FSM concepts, especially how Mealy machines react immediately to inputs.

---

## 💡 What It Does

The circuit takes a serial stream of bits (`1s` and `0s`) and checks whether the pattern `101` appears. If it does, the output goes high (`1`) **for one clock cycle**.

- ✅ **Overlapping allowed**  
  For example, in `10101`, it detects two sequences.
- ✅ **Fast response**  
  Output is high as soon as the sequence is recognized — that’s how a Mealy machine works!

---

## 🧠 How It Works (States)

The FSM moves through states based on the input:

