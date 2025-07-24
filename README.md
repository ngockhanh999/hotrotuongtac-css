# hotrotuongtac-css
Hotrotuongtac.vn
/* Link CSS Section for User Only */
.view-user .httt-link-css-container {
    max-width: 600px;
    margin: 40px auto;
    padding: 20px;
    background: linear-gradient(135deg, #1a73e8, #4dabf5);
    border-radius: 12px;
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
    color: #ffffff;
}

.view-user .httt-link-css-title {
    font-size: 1.5em;
    font-weight: 600;
    margin-bottom: 20px;
    text-align: center;
    text-transform: uppercase;
}

.view-user .httt-link-css-input-wrapper {
    position: relative;
    margin-bottom: 20px;
}

.view-user .httt-link-css-input {
    width: 100%;
    padding: 12px 15px;
    border: 2px solid #ffffff;
    border-radius: 8px;
    background: rgba(255, 255, 255, 0.1);
    color: #ffffff;
    font-size: 1em;
    outline: none;
    transition: border-color 0.3s ease, box-shadow 0.3s ease;
}

.view-user .httt-link-css-input:focus,
.view-user .httt-link-css-input:hover {
    border-color: #4dabf5;
    box-shadow: 0 0 10px rgba(77, 171, 245, 0.5);
}

.view-user .httt-link-css-label {
    position: absolute;
    top: 10px;
    left: 15px;
    font-size: 1em;
    color: #ffffff;
    transition: all 0.3s ease;
    pointer-events: none;
}

.view-user .httt-link-css-input:focus + .view-user .httt-link-css-label,
.view-user .httt-link-css-input:not(:placeholder-shown) + .view-user .httt-link-css-label {
    top: -10px;
    font-size: 0.9em;
    color: #4dabf5;
}

.view-user .httt-link-css-instructions {
    font-size: 0.9em;
    line-height: 1.5;
    color: #e0e0e0;
    padding: 10px;
    background: rgba(0, 0, 0, 0.2);
    border-radius: 6px;
}

.view-user .httt-link-css-instructions strong {
    color: #ffffff;
}

@media (max-width: 768px) {
    .view-user .httt-link-css-container {
        margin: 20px;
        padding: 15px;
    }

    .view-user .httt-link-css-title {
        font-size: 1.3em;
    }

    .view-user .httt-link-css-input {
        padding: 10px 12px;
    }
}

@media (max-width: 480px) {
    .view-user .httt-link-css-container {
        margin: 10px;
        padding: 10px;
    }

    .view-user .httt-link-css-title {
        font-size: 1.1em;
    }

    .view-user .httt-link-css-input {
        padding: 8px 10px;
    }

    .view-user .httt-link-css-instructions {
        font-size: 0.8em;
    }
}
