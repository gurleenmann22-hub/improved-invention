body {
  font-family: Arial, sans-serif;
}

button {
  cursor: pointer;
}

.modal-overlay {
  position: fixed;
  inset: 0;
  background: rgba(0, 0, 0, 0.4);
  display: none;
  justify-content: center;
  align-items: center;
}

.modal {
  background: #fff;
  width: 420px;
  border-radius: 10px;
  padding: 20px;
}

.modal-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.close-btn {
  font-size: 22px;
  cursor: pointer;
}

label {
  display: block;
  margin-top: 15px;
  font-weight: bold;
}

input[type="url"] {
  width: 100%;
  padding: 10px;
  margin-top: 5px;
  border-radius: 6px;
  border: 1px solid #ccc;
}

.section-title {
  margin-top: 20px;
}

.radio-group label {
  display: block;
  margin-top: 10px;
  font-weight: normal;
}

.radio-group span {
  display: block;
  font-size: 13px;
  color: #666;
  margin-left: 22px;
}

.modal-actions {
  display: flex;
  justify-content: flex-end;
  margin-top: 20px;
  gap: 10px;
}

.cancel {
  background: #eee;
  border: none;
  padding: 10px 15px;
  border-radius: 6px;
}

.save {
  background: #2e7d6b;
  color: white;
  border: none;
  padding: 10px 18px;
  border-radius: 6px;
}
