<<<<<<< SEARCH
=======
// Interface for button elements
interface ButtonProps {
    href: string;
}

export class Button {
    private content: string;
    private style: {
        marginTop: number;
        paddingRight: number;
    };

    constructor(content: string, style: { marginTop: number; paddingRight: number }) {
        this.content = content;
        this.style = style;
    }

    render() {
        return `<button href="${this.href}">${this.content}</button>`;
    }

    hover() {
        return this.style.paddingRight += 10;
    }
}

// Interface for highlighted text
interface HighlightTextProps {
    text: string;
    style: {
        fontSize: number;
        color: string;
    };
}

export class HighlightText {
    private text: string;
    private style: {
        fontSize: number;
        color: string;
    };

    constructor(text: string, style: { fontSize: number; color: string }) {
        this.text = text;
        this.style = style;
    }

    render() {
        return `<div style="font-size: ${this.fontSize}; color: ${this.color})">${this.text}</div>`;
    }
}

// Example usage:
// <HighlightText text="Dynamic highlighting!" style={{ fontSize: 64, color: '#00ff88' }} />
// <Button href="#" content="Learn More" style={{ marginTop: 20, paddingRight: 100 }} />
>>>>>>> REPLACE
