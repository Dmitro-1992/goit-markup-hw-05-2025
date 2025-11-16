# goit-markup-hw-01-2025

my-first-project-2025

.modal-overlay.is-open {
opacity: 1;
pointer-events: auto;
} 

.modal {
    position: absolute;
box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.14), 0 1px 3px 0 rgba(0, 0, 0, 0.12), 0 2px 1px 0 rgba(0, 0, 0, 0.2);
background-color: var(--dairy);
border-radius: 4px;
padding: 16px;
box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.14), 0 1px 3px 0 rgba(0, 0, 0, 0.12), 0 2px 1px 0 rgba(0, 0, 0, 0.2);
width: 408px;
min-height: 80%;
overflow-y: auto;
}
.modal-svg {
display: flex;
justify-content: flex-end;
align-items: center;
}
.modal-text {
    font-weight: 500;
    font-size: 16px;

    line-height: 24px;
    line-height: 1.5;
    letter-spacing: 0.02em;
    text-align: center;
    color: var(--navy-blue);
    margin-bottom: 16px;
}
.form {
display: flex;
    align-items: flex-start;
    justify-content: flex-start;
    flex-direction: column;
    gap: 8px;
    border-radius: 4px;
        width: 360px;
        height: 336px;
}
.form-button {
    align-self: flex-start;
}


.form-input::placeholder {
    color: #616161;
}

.form-label {
    display: flex;
    flex-direction: column;
    width: 360px;
    height: 58px;

}

.form-label:focus-within {
    color: #009688;
} 
/* #endregion backdrop-modal  */
 


<!-- 
  <svg class="modal-svg" width="8" height="8" viewBox="0 0 8 8" fill="none" xmlns="http://www.w3.org/2000/svg">
  <g clip-path="url(#clip0_992990_440)">
    <path d="M8 0.805714L7.19429 0L4 3.19429L0.805714 0L0 0.805714L3.19429 4L0 7.19429L0.805714 8L4 4.80571L7.19429 8L8 7.19429L4.80571 4L8 0.805714Z" fill="#2E2F42" />
  </g>
  <defs>
    <clipPath id="clip0_992990_440">
      <rect width="8" height="8" fill="white" />
    </clipPath>
  </defs>
</svg> -->