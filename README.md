# Beyond 3D Convolutions: A 4D Transformer-Based Network for Capturing Vascular Kinetics in Neoadjuvant Chemotherapy Response Prediction

📄 **[Click here to view or download the PDF](./YOUR_PAPER_FILENAME.pdf)**

---

## Abstract

Neoadjuvant chemotherapy (NAC) is commonly administered before surgery in patients with advanced breast cancer, particularly those with nodal involvement, large tumors, or aggressive biologic subtypes such as inflammatory, HER2-positive, and triple-negative disease. Despite the well-established benefits of NAC, many patients do not respond to treatment, highlighting the need for improved response prediction. Delays introduced by ineffective NAC may contribute to decreased treatment success rates in addition to the common adverse effects of chemotherapy. Although deep learning models have been proposed to predict patient response to NAC, accuracy is often limited by unavailable clinical information to contextualize MRI features, reliance on expert-engineered features beyond tumor masks, and the disregard or simplification of temporal dynamics of the administered contrast. We propose a new 4D transformer-based architecture to predict NAC response from variable length pre-treatment dynamic contrast enhanced MRI (DCE-MRI) sequences. Unlike other state-of-the-art models, we use a deep patch embedding network that leverages spatiotemporal multi-head self-attention to map the physiological progression of contrast agent washout. By capturing complex perfusion dynamics, the proposed 4D attention mechanism transforms dynamic anatomical information into enriched representations that improve the predictions of complete response to NAC. Our model was trained and evaluated on a public dataset with pre-treatment DCE-MRI from 1,506 patients with breast cancer who underwent NAC. It outperformed state-of-the-art models with an AUC of 0.73 (69.09% balanced accuracy, 75.27% sensitivity, 62.91% specificity) in the highly challenging task of predicting NAC response. Our framework could support early patient stratification towards more efficient treatments to improve personalized prognosis.

---

## Citation

If you use or reference this paper, please cite it as:

```bibtex
@article{stoughton2026beyond,
  title={Beyond 3D Convolutions: A 4D Transformer-Based Network for Capturing Vascular Kinetics in Neoadjuvant Chemotherapy Response Prediction},
  author={Thomas E Stoughton, Randy C Miles, Ines A Cruz-Guerrero, Antonio R Porras},
  year={2026}
}
