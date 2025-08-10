# 🎨 DocuCraft AI - Smart Document Generator

Transform raw text into professional documents with AI-powered analysis and intelligent format suggestions.

## ✨ Features

### 🧠 Smart Text Analysis
- **Automatic Structure Detection**: Identifies headings, tables, lists, and content hierarchy
- **Content Type Classification**: Determines optimal document format based on text structure
- **Intelligent Recommendations**: Suggests best file formats with confidence scores
- **Advanced NLP Processing**: Uses NLTK and custom algorithms for text analysis

### 📄 Multiple Output Formats
- **Word (.docx)**: Professional documents with styling, headers, and formatting
- **PDF**: Print-ready documents with beautiful layouts and color schemes
- **Excel (.xlsx)**: Structured data with professional styling and formatting
- **CSV**: Clean data export for analysis and import
- **JSON**: Structured data for applications and APIs
- **ODS**: Open Document Spreadsheet format

### 🎨 Beautiful UI Design
- **Modern Interface**: Gradient backgrounds and professional styling
- **Responsive Layout**: Works perfectly on all screen sizes
- **Interactive Components**: Hover effects and smooth transitions
- **Perfect Color Combinations**: Carefully selected color schemes for optimal UX

### 🔍 Advanced Content Detection
- **Table Recognition**: Detects CSV-like data with various separators (commas, tabs, pipes)
- **Heading Hierarchy**: Identifies markdown headers, title case, and uppercase headings
- **List Detection**: Recognizes bullet points, numbered lists, and lettered lists
- **Mixed Content**: Handles documents with multiple content types

## 🚀 Quick Start

### Prerequisites
- Python 3.8+ (tested with Python 3.13)
- Virtual environment (recommended)

### Installation

1. **Clone or download the project**
   ```bash
   cd /path/to/DocuCraft-AI
   ```

2. **Create and activate virtual environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   streamlit run app.py
   ```

5. **Open your browser**
   Navigate to `http://localhost:8501` to access the application.

## 📊 How It Works

### 1. Text Input
- Paste your raw text content into the input area
- Supports various content types: tabular data, documents, lists, mixed content
- Real-time character, word, and line counting

### 2. AI Analysis
- **Structure Detection**: Analyzes text for patterns and structure
- **Content Classification**: Determines the primary content type
- **Confidence Scoring**: Provides reliability scores for recommendations
- **Format Suggestions**: Ranks output formats by suitability

### 3. Document Generation
- **Professional Formatting**: Creates documents with proper styling
- **Color Schemes**: Uses beautiful, professional color combinations
- **Template-Based**: Applies appropriate templates based on content type
- **Quality Output**: Ensures professional, print-ready results

### 4. Preview & Download
- **Live Preview**: See formatted content before downloading
- **Multiple Formats**: Generate and download in various formats
- **Instant Access**: One-click download with proper file naming

## 📋 Supported Content Types

### Tabular Data
- **CSV-like content** with commas, tabs, or pipes as separators
- **Automatic column detection** and header identification
- **Best for**: Excel, CSV, ODS formats

**Example:**
```
Name, Department, Score, Rating
John Smith, Engineering, 95, Excellent
Sarah Johnson, Design, 88, Good
```

### Structured Documents
- **Clear headings** and section hierarchy
- **Organized content** with multiple levels
- **Best for**: Word, PDF formats

**Example:**
```
# Project Report

## Executive Summary
This project achieved significant milestones...

## Key Findings
- Finding 1: Performance improved by 25%
- Finding 2: User satisfaction increased
```

### Lists and Bullets
- **Bullet points** and numbered lists
- **Mixed list types** in single document
- **Best for**: Word, PDF formats

**Example:**
```
Project Tasks:
• Website redesign - 75% complete
• Mobile app development - 50% complete
• Database migration - 90% complete

Next Steps:
1. Complete remaining components
2. Begin testing phase
3. Prepare documentation
```

### Mixed Content
- **Combination** of tables, headings, and lists
- **Complex documents** with varied structure
- **Best for**: Word, Excel, JSON formats

## 🎯 Format Recommendations

The AI analyzes your content and provides intelligent format suggestions:

### 🌟 Excellent Match (90-100%)
- Perfect content-format alignment
- Optimal structure preservation
- Professional output quality

### ⭐ Good Match (75-89%)
- Good content-format compatibility
- Most features preserved
- High-quality output

### 📄 Basic Match (50-74%)
- Acceptable format choice
- Some features may be simplified
- Functional output

## 🛡️ Edge Cases Handled

### Input Validation
- **Empty content** detection and warnings
- **Malformed data** identification and correction
- **Large text** processing optimization
- **Special characters** proper encoding support

### Error Handling
- **Format conflicts** resolution with fallback options
- **Generation failures** with helpful error messages
- **Preview errors** with graceful degradation
- **Download issues** with retry mechanisms

### Performance Optimization
- **Efficient text processing** for large documents
- **Memory management** for file generation
- **Responsive UI** during processing
- **Background processing** for large files

## 🎨 Design Philosophy

### Color Schemes
- **Professional palette**: Blues, grays, and whites for business documents
- **Modern gradients**: Smooth color transitions for visual appeal
- **Accessibility**: High contrast ratios for readability
- **Consistency**: Unified color language throughout the application

### User Experience
- **Intuitive navigation**: Clear tabs and logical flow
- **Visual feedback**: Progress indicators and status messages
- **Responsive design**: Works on desktop, tablet, and mobile
- **Minimal clicks**: Streamlined workflow from input to download

## 🔧 Technical Details

### Architecture
- **Frontend**: Streamlit with custom CSS styling
- **Text Analysis**: NLTK, custom regex patterns, statistical analysis
- **Document Generation**: python-docx, reportlab, openpyxl, odfpy
- **Data Processing**: pandas for structured data handling

### Key Components
1. **TextAnalyzer**: Advanced text structure detection and classification
2. **DocumentGenerator**: Multi-format document creation with professional styling
3. **UI Components**: Beautiful, responsive interface with perfect color combinations
4. **Error Handling**: Comprehensive edge case management

### Dependencies
- `streamlit`: Web application framework
- `pandas`: Data manipulation and analysis
- `python-docx`: Word document generation
- `reportlab`: PDF creation and styling
- `openpyxl`: Excel file generation
- `odfpy`: Open Document format support
- `nltk`: Natural language processing
- `textstat`: Readability analysis
- `plotly`: Interactive visualizations
- `streamlit-option-menu`: Enhanced navigation

## 📈 Performance

### Processing Speed
- **Small texts** (< 1KB): Instant analysis and generation
- **Medium texts** (1-100KB): < 5 seconds processing
- **Large texts** (> 100KB): Optimized streaming processing

### Output Quality
- **Professional formatting** with proper fonts and spacing
- **Color consistency** across all generated documents
- **Print-ready quality** for PDF and Word formats
- **Data integrity** preserved in all transformations

## 🤝 Contributing

This project demonstrates advanced text processing, document generation, and UI design. Key areas for enhancement:

1. **Additional Formats**: PowerPoint, HTML, Markdown
2. **Advanced Analysis**: Sentiment analysis, keyword extraction
3. **Collaboration Features**: Multi-user editing, version control
4. **Cloud Integration**: Google Drive, Dropbox, OneDrive
5. **API Endpoints**: RESTful API for programmatic access

## 📄 License

Built with ❤️ using modern Python frameworks and libraries. Demonstrates best practices in:
- Text processing and NLP
- Document generation and formatting
- User interface design
- Error handling and edge cases
- Performance optimization

---

**Ready to transform your raw text into professional documents? Launch the app and experience the power of AI-driven document generation!** 🚀